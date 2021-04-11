  
<template>
  <div>
    <UserHeader></UserHeader>
    <router-view></router-view>
    <CartIcon></CartIcon>
    <!-- <UserFooter></UserFooter> -->
  </div>
</template>
<script>
import UserHeader from "@/customerpages/components/UserHeader";
// import UserFooter from "@/components/User/UserFooter";
 import CartIcon from "@/customerpages/components/CartIcon";
// import Alert from "@/components/Alert";
export default {
  data() {
    return {};
  },
  components: {
    UserHeader,
    // UserFooter,
    CartIcon,
    // Alert
  }
};
</script>