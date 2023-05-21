<template>
    <section id="notice">
        <div v-for="item in data.slice(0, 1)" :key="item.id">
            <ui :id="item.id">
                <li></li>
                <li>{{ item.title }}</li>
                <li>{{ item.description }}</li>
                <li id="notice-more">더보기</li>
            </ui>
        </div>
    </section>
</template>
    
<script>
import notice from "/static/notice.json";

export default {
    name: 'section',
    data() {
        return {
            data:notice
        }
    }
};
</script>

<style scoped>
#notice {
    width: calc(100% - 10px);
    padding-top: 15px;
    padding-bottom: 15px;
    padding-left: 10px;
    border-radius: 10px;
    border: 1px solid #212121;
}

#notice-more {

}
</style>