<template>
     <div class="subject-card-wrapper">
        <chat-room-haru-ask-comp></chat-room-haru-ask-comp>
    </div>
</template>
<script>
import ChatRoomHaruAskComp from '@/modules/chatwithharubot/components/ChatRoomHaruAskComp.vue';
export default {
  name: "ChatRoomHaruAskView",
  components: {
        ChatRoomHaruAskComp
    }
}
</script>

<script setup>

</script>

<style scoped>
:root {
  --v-layout-top: 0px;
}
/* 스크롤바 관련 설정 */
.subject-card-wrapper {
  height: 600px;
  overflow-y: auto;
  margin-top: 10px;
  margin-bottom: 60px;
}

/* 스크롤바 숨기기 */
.subject-card-wrapper::-webkit-scrollbar {
  display: none;
}

</style>