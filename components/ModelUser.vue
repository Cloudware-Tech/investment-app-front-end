<template>
    <v-card
        max-width="400"
    >
        
        <!-- <ImageEl src="https://cdn.vuetifyjs.com/images/cards/docks.jpg" height="200" /> -->

        <v-card-subtitle class="pb-0">
            <span class="tw-font-bold tw-text-black tw-text-base">Beans management</span>
        </v-card-subtitle>

        <v-card-text class="text--primary">
            <div class="">
                &#8358; 40,000
                <span class="tw-bg-blue-300 tw-bg-opacity-10 tw-p-1
                 tw-rounded-sm tw-text-blue-800 tw-text-xs">
                    Fixed per square meter
                </span>
            </div>
            <div class="tw-pt-2">
                <span class="tw-bg-green-300 tw-bg-opacity-10 tw-p-1
                 tw-rounded-sm tw-text-green-800 tw-text-xs">
                    Supports co-ownership
                </span>
            </div>
            <div class="tw-pt-2">
                Model description model description model description model description model
            </div>
        </v-card-text>

        <v-card-actions>
            <v-btn
                color="primary"
                text
                small
            >
                More details
            </v-btn>
        </v-card-actions>
    </v-card>
</template>

<script>
    import ImageEl from "@/components/ImageEl.vue"
    export default {
        components:{
            ImageEl
        }
    }
</script>