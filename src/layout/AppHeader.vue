<template>
    <header class="header-global fixed-top">
        <base-nav class="bg-default fixed-top" transparent type="" effect="light" expand>
            <a class="navbar-brand mr-lg-5 no-show-on-sm" href="https://amadeus.video">
                <img src="img/logo-white.png" alt="logo" style="width: 150px; height: auto;">
            </a>
 
            <!-- For Mobile View -->
            <div class="row" slot="content-header" slot-scope="{closeMenu}">
                <div class="col-6 collapse-brand">
                    <a href="https://www.amadeus.video">
                        <img src="img/logo-blue.png">
                    </a>
                </div>
                <div class="col-6 collapse-close">
                    <close-button @click="closeMenu"></close-button>
                </div>
            </div>

            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <a slot="title" href="/" class="nav-link" data-toggle="dropdown" role="button">
                    <span class="nav-link-inner--text">Home</span>
                </a>
                <a slot="title" href="/pricing" class="nav-link" data-toggle="dropdown" role="button">
                    <span class="nav-link-inner--text">Pricing</span>
                </a>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://www.my.amadeus.video/login" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                        <span class="btn-inner--icon">
                        <i class="ni ni-circle-08 mr-2"></i>
                        </span>
                        <span class="nav-link-inner--text">Register</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
@media (max-width: 768px) {
    .show-on-sm {
        display: inline !important;
    }

    .no-show-on-sm {
        display: none !important;
    }
}

@media (min-width: 769px) {
    .smaller-title {
        font-size: 10px !important;
    }
    .show-on-lg {
        display: inline !important;
    }

    .no-show-on-lg {
        display: none !important;
    }
}
</style>
