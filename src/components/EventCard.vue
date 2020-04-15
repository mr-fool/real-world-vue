<template>
    <div>
        <span>@{{event.time}} on {{event.date}}</span>
        <h4> {{event.title}} </h4>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                event: {
                    id: 1,
                    title: "Test",
                    date: "April 15, 2020",
                    time: "6:30",
                    attendees: [
                        {id: 'abc123', name: "test user"},
                        {id: 'def456', name: "test user2"}
                    ]
                }
            }
        },
    }
</script>

<style scoped>
    h4 {
        color: green;
    }
</style>