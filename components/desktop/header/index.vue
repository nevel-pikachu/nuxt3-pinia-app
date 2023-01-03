<template>
    <div class="header_section header">
        <div class="header__logo logo">
            <nuxt-link to="/">
                <span class="logo__content">VinEX</span>
            </nuxt-link>
        </div>
        <div class="header__menu menu">
            <base-dropdown title-classes="btn btn-secondary" title="Regular">
                <a class="dropdown-item" href="#">Action</a>
                <a class="dropdown-item" href="#">Another action</a>
                <a class="dropdown-item" href="#">Something else here</a>
            </base-dropdown>
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
        padding: 16px 20px;
    }   
    .header {
        &__logo {
            flex: 1;
            width: 122px;
            height: 32px;
        }
        
        .logo {
            &__content {
                font-size: 42px;
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
            display: flex;
            justify-content: right;
            
            &__wallet_linked {
                width: 160px;
                height: 48px;
                background-color: #FAAC2E;
                border-radius: 8px;
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