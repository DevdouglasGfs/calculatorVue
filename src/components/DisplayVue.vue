<template>
    <div class="display">
        <div class="display__show-results">
            <span class="latest-operation">{{ latestOperation }}</span>
            <p class="result">{{ result }}</p>
        </div>
        <div class="calculator">
            <div class="calculator__logic-operators">
                <div class="calculator__logic-operators-top">
                    <div class="calculator__logic-operator">
                        <span id="ac">AC</span>
                    </div>
                    <div class="calculator__logic-operator">
                        <span id="srqt"><i class="fa-solid fa-square-root-variable"></i></span>
                    </div>
                    <div class="calculator__logic-operator">
                        <span id="add"><i class="fa-solid fa-plus"></i></span>
                    </div>
                    <div class="calculator__logic-operator">
                        <span id="minus"><i class="fa-solid fa-minus"></i></span>
                    </div>
                    <div class="calculator__logic-operator">
                        <span id="result"><i class="fa-solid fa-equals"></i></span>
                    </div>
                </div>
                <div class="calculator__logic-operators-right">
                    
                </div>
                <div class="calculator__digits">
                <div class="digit">
                    <span>1</span>
                </div>
                <div class="digit">
                    <span>2</span>
                </div>
                <div class="digit">
                    <span>3</span>
                </div>
                <div class="digit">
                    <span>4</span>
                </div>
                <div class="digit">
                    <span>5</span>
                </div>
                <div class="digit">
                    <span>6</span>
                </div>
                <div class="digit">
                    <span>7</span>
                </div>
                <div class="digit">
                    <span>8</span>
                </div>
                <div class="digit">
                    <span>9</span>
                </div>
                <div class="digit">
                    <span>0</span>
                </div>
            </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'DisplayVue',
    props: {
        msg: String,
        latestOperation: String,
        result: String
    }
}
</script>

<style scoped lang="scss">

</style>