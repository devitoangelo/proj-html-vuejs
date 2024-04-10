<script>
export default {

}
</script>

<template>
    <!-- header -->
    <header id="header">
        <!-- container -->
        <div class="site_header">
            <!-- logo -->
            <img class="logo" width="100px" src="/images/Logo.jpg" alt="">
            <!-- lista header -->
            <ul class="d-flex header_list ">
                <li class="hover_click">
                    <strong>Home</strong>
                </li>
                <li class="hover_click">
                    <strong>About</strong>
                    
                </li>
                <li class="hover_click">
                    <strong>Academics</strong>
                    
                </li>
                <li class="hover_click">
                    <strong>Courses</strong>
                    

                </li>
                <li class="hover_click">
                    <strong>News</strong>
                    

                </li>
            </ul>





        </div>
    </header>
</template>



<style>
#header {

    width: 100%;
    height: 70px;

    >.site_header {

        width: 70%;
        height: 100%;
        margin: auto;
        display: flex;
        justify-content: space-between;

        >.header_list {
            list-style: none;
            gap: 2rem;
            align-items: center;

        }
        >.logo{
          margin-bottom: -1rem;
        }

    }
}

.hover_click:hover{
    text-decoration: underline;
    color: red;
    
}
</style>