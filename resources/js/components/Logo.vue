<template>
    <div>
        <h1 class="font-normal text-3xl text-grey-darkest leading-none mb-8">
            Full Logo
        </h1>
        
        <div class="mb-10">
            <picture style="height: 382px;" class="block shadow rounded-lg flex items-center justify-center mb-6">
                <img src="/images/logo.svg" alt="logo"/>
            </picture>
    
            <div class="flex justify-between items-center">
                <p>
                    Original Logo on <strong>white</strong> background
                </p>
        
                <a href="/images/logo.svg" class="button">logo.svg</a>
            </div>
        </div>

        <div class="mb-10">
            <picture style="height: 382px;" class="block shadow rounded-lg flex items-center justify-center mb-6 bg-blue">
                <img src="/images/negative-logo.svg" alt="negative-logo"/>
            </picture>
    
            <div class="flex justify-between items-center">
                <p>
                    Negative Logo with accent on <strong>dark</strong> background
                </p>
        
                <a href="/images/negative-logo.svg" class="button">negative-logo.svg</a>
            </div>
        </div>
        <div>
            <picture style="height: 382px;" class="block shadow rounded-lg flex items-center justify-center mb-6 bg-black">
                <img src="/images/negative-pure-logo.svg" alt="negative-pure-logo"/>
            </picture>
    
            <div class="flex justify-between items-center">
                <p>
                    Pure negative logo on <strong>dark</strong> background
                </p>
        
                <a href="/images/negative-logo.svg" class="button">negative-pure-logo.svg</a>
            </div>
        </div>
    </div>
    
</template>


<script>
export default {
    
}
</script>