<script>
export default {
    
}
</script>

<template>
    <footer>
    <!-- input_footer -->
    <div class="site_footer">
      <div class="footer">
        <div class="templete_footer">
          <input placeholder="Subscribe to our newsletter" class="input_text">
          <button class="buttom"> Register</button>
          <section class="text_footer">
            <nav class="color_text">
              Insights is Picwik
            </nav>
            <nav style="color: var(--color_text);">
              university's thought leadership publication for sharing
            </nav>
          </section>
        </div>
      </div>

      <!-- list_footer -->
      <div class="list_footer">
        <div class="contanier-info">
          <aside>
            <h2>Contact Us</h2>
            <div class="info_footer">
              <section class="pb-2 hover_footer"><i class="fa-solid fa-location-dot"></i> 900 Wood Street,Mi <br> New
                York 48607
              </section>
              <section class="pb-2 hover_footer"><i class="fa-solid fa-square-phone"></i> +56 784 442 378-09 </section>
              <section class="hover_footer"><i class="fa-regular fa-envelope"></i> info@example.com</section>
            </div>
          </aside>

          <aside>
            <h2>Support Us</h2>
            <div class="info_footer">
              <section class="pb-2 hover_footer">> Privacy</section>
              <section class="pb-2 hover_footer">> Terms</section>
              <section class="pb-2 hover_footer">> Cookie policy</section>
              <section class="hover_footer">> Sitemap</section>
            </div>
          </aside>


          <aside>
            <h2>Explore</h2>
            <div class="info_footer">
              <section class="pb-2 hover_footer">> Accommodation</section>
              <section class="pb-2 hover_footer">> Arts Academics</section>
              <section class="pb-2 hover_footer"> > central Services </section>
              <section class="pb-2 hover_footer">> Conferences and Events</section>
              <section class="hover_footer">> Food and Drink </section>
            </div>
          </aside>


          <aside>
            <h2>Visit</h2>
            <div class="info_footer hover_footer">
              <section class="pb-2 hover_footer"> > Admision</section>
              <section class="pb-2 hover_footer">> Contact Us</section>
              <section class="pb-2 hover_footer">> FAQs</section>
              <section class="pb-2 hover_footer">> Request information</section>
              <section class="hover_footer">> Privacy notice</section>
            </div>
          </aside>
        </div>
      </div>
    </div>
    <!-- footer_copy -->
    <div class="footer_copy">
      <div class="copy">
        <nav>
          &#169; Copyright 2020 tophive. all rights Reserved
        </nav>
        <ul class="list_footer_copy">
          <li>
            Privacy
          </li>
          <li>
            Terms
          </li>
          <li>
            Cookie Policy
          </li>
          <li>
            Sitemap
          </li>
        </ul>

      </div>


    </div>
  </footer>

</template>

<style>

/* footer */
/* input_footer */
.site_footer {
  background-color: var(--bg_footer);
  height: 500px;
  width: 100%;
  padding-top: 5rem;

  >.footer {
    margin: auto;
    width: 70%;
    background-color: var(--color);
    height: 150px;
    display: flex;

    >.templete_footer {
      margin: auto;
      width: 90%;
      background-color: var(--color);
      height: 40%;
      display: inline-flex;
      align-items: center;

      >.input_text {
        height: 100%;
        width: 25%;
        text-decoration: none;

      }

      >.buttom {
        background-color: var(--ResultOnlineCourse);
        height: 80%;
        width: 15%;
        color: white;
        border: none
      }

      >.text_footer {
        display: flex;
        height: 90%;
        margin-left: 2rem;

        >.color_text {
          color: var(--color_subtitle);
          text-decoration: underline;
          margin-right: 0.5rem;
        }
      }

    }

  }
}

/* list_footer */

.list_footer {
  color: white;
  margin-top: 3rem;


  >.contanier-info {
    display: flex;
    justify-content: space-evenly;

  }
}

.info_footer {
  color: var(--color_text);
}

/* footer_copy */
.footer_copy {
  background-color: var(--color);
  height: 50px;
  width: 100%;
  display: flex;

  >.copy {
    width: 70%;
    margin: auto;
    height: 100%;
    display: flex;
    font-size: x-small;
    justify-content: space-between;
    color: var(--color_footer);
    line-height: 3;
  }
}

.list_footer_copy {

  list-style: none;
  display: flex;
  gap: 1rem;
  align-items: center;
}

.hover_footer:hover {
  color: var(--color_subtitle);
}
    
</style>