<template>
        <div class="notify_input py-2">
              <b-form-input
                class="for_place text-white my-2"
                v-model="text"
                placeholder="Send push notification"
                style="width: 300px"
              ></b-form-input>
              <button class="send setup m-2">
                Send
              </button>
          </div>
</template>