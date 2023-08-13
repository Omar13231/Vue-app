<template>
<section>
    <h2> My friends </h2>
    <ul>
        <friend-contact></friend-contact>
    </ul>
</section>
</template>
<script>
export default {
    data(){
        return{
            friends: [
                {
                    id: 'manuel',
                    name : 'manuel lorenz',
                    phone: '01827747378',
                    email: 'joan@local.com'
                },
                {
                    id: 'ferrera',
                    name : 'hana ferrera',
                    phone: '01827747378',
                    email: 'hanah@local.com'
                }
            ]
        }
    }
}
</script>