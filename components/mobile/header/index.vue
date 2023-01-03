<template>
    <div class="header_section header ">
        <div class="header__menu menu">
            <img src="_nuxt/assets/images/menu.svg"/>
        </div>
        <div class="header__logo logo">
            <nuxt-link to="/">
                <span class="logo__content">VinEX</span>
            </nuxt-link>
        </div>
        
        <div class="header__action action">
            <button class="action__wallet_linked">
                Liên kết ví
            </button>
        </div>
    </div>
</template>

<script>
</script>

<style scope lang="scss">
    .header_section {
        display: flex;
        padding: 16px 0px 16px 16px;
    }   
    .header {
        &__logo {
            flex: 1;
            width: 122px;
            height: 32px;
        }
        
        .logo {
            &__content {
                font-size: 24px;
                color: #FAAC2E;
            }   
        }

        &__menu {
            max-width: 24px;
            margin-top: 6px;
            margin-right: 4px;
        }

        &__action {
            flex: 1;
        }
        .action {
            &__wallet_linked {
                width: 120px;
                height: 30px;
                background-color: #FAAC2E;
                border-radius: 8px;
                color: #FFFFFF;
                &:hover,
                &:focus {
                    animation: pulse 1s;
                    box-shadow: 0 0 0 2em transparent;
                }
            }
        }
    }
    @keyframes pulse {
        0% { box-shadow: 0 0 0 0 adjust-hue(#ef6eae, 45deg); }
    }
    @-webkit-keyframes pulse {
        0% { box-shadow: 0 0 0 0 var(--hover); }
    }
</style>