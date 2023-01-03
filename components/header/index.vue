<template>
    <div class="header_section header">
        <div class="header__logo logo">
            <span class="logo__content">VinEX</span>
        </div>
        <div class="header__menu menu">
            <div class="">Menu</div>
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
        margin-top: 10px;
    }   
    .header {
        &__logo {
            flex: 1;
            width: 122px;
            height: 32px;
        }
        
        .logo {
            &__content {
                font-size: 28px;
                color: #FAAC2E;
            }
        }

        &__menu {
            flex: 5;
        }

        &__action {
            flex: 1;
        }
        .action {
            &__wallet_linked {
                width: 160px;
                height: 48px;
                background-color: #FAAC2E;
                border-radius: 8px;
            }
        }
    }
</style>