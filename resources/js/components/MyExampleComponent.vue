<template>
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-md-8">
                <div class="card">
                    <div class="card-header">Example Component 2</div>

                    <div class="card-body">
                            <postal-code v-model="postal_code" 
                            /> {{ postal_code }}
                    </div>
                </div>
            </div>
        </div>
    </div>
   
</template>

<script>

    export default {
        data(){
            return {
                postal_code:'l3r3g',
            }

        },
    }
</script>
