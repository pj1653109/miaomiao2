<template>
    <div id="main">
        <Header title="我的喵喵" />
        <div id="content">
            <Login />
        </div>
        <TaBar />
    </div>
</template>
<script>
import Header from '@/components/Header';
import TaBar from '@/components/TaBar';
import Login from '@/components/Login';

export default {
    name : 'Mine',
    components : {
        Header,
        TaBar,
        Login
    }
}
</script>
<style>
</style>