<template>
  <div class="home">
    <div class="overlay"></div>

    <!-- Preloader -->
    <div class="preloader">
      <div class="loader-wrapper">
        <div class="truck-wrapper">
          <div class="preloader-content">ViserBus</div>
          <div class="truck">
            <div class="truck-container"></div>
            <div class="glases"></div>
            <div class="bonet"></div>

            <div class="base"></div>

            <div class="base-aux"></div>
            <div class="wheel-back"></div>
            <div class="wheel-front"></div>
            <div class="smoke"></div>
          </div>
        </div>
      </div>
    </div>
    <!-- Preloader -->
    <!-- Header Section Starts Here -->

    <div class="header-top">
      <div class="container">
        <div class="header-top-area">
          <ul class="left-content">
            <li>
              <i class="las la-phone"></i>
              <a href="tel:+44 45678908">
                +44 45678908
              </a>
            </li>
            <li>
              <i class="las la-envelope-open"></i>
              <a href="https://script.viserlab.com/cdn-cgi/l/email-protection#7b1e031a160b171e3b1c161a121755181416">
                <span class="__cf_email__" data-cfemail="c6a3bea7abb6aaa386a1aba7afaae8a5a9ab">[email&#160;protected]</span>
              </a>
            </li>
          </ul>
          <div class="right-content d-flex flex-wrap" style="gap:10px">
            <div>
              <select class="langSel form--control">
                <option value="en"  selected >English</option>
                <option value="hn" >Hindi</option>
                <option value="bn" >Bangla</option>
              </select>
            </div>
            <ul class="header-login">
              <li><a class="sign-in" href="login.html"><i class="fas fa-sign-in-alt"></i>Sign In</a></li>
              <li>/</li>
              <li><a class="sign-up" href="register.html"><i class="fas fa-user-plus"></i>Sign Up</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="header-bottom">
      <div class="container">
        <div class="header-bottom-area">
          <div class="logo">
            <a href="https://script.viserlab.com/viserbus">
              <img src="assets/images/logoIcon/logo.png" alt="Logo">
            </a>
          </div> <!-- Logo End -->
          <ul class="menu">
            <li>
              <a href="https://script.viserlab.com/viserbus">Home</a>
            </li>
            <li>
              <a href="about-us.html">About</a>
            </li>
            <li>
              <a href="faq.html">FAQs</a>
            </li>

            <li>
              <a href="blog.html">Blog</a>
            </li>
            <li>
              <a href="contact.html">Contact</a>
            </li>
          </ul>
          <div class="d-flex flex-wrap algin-items-center">
            <a href="tickets.html" class="cmn--btn btn--sm">Buy Tickets</a>
            <div class="header-trigger-wrapper d-flex d-lg-none ms-4">
              <div class="header-trigger d-block d-lg-none">
                <span></span>
              </div>
              <div class="top-bar-trigger">
                <i class="las la-ellipsis-v"></i>
              </div>
            </div><!-- Trigger End-->
          </div>
        </div>
      </div>
    </div>

    <!-- Header Section Ends Here -->


    <!-- Banner Section Starts Here -->
    <section class="banner-section" style="background: url(assets/images/frontend/banner/61f118f07f1151643190512.png) repeat-x bottom;">
      <div class="container">
        <div class="banner-wrapper">
          <div class="banner-content">
            <h1 class="title">Get Your Ticket Online, Easy and Safely</h1>
            <a href="tickets.html" class="cmn--btn">Get ticket now</a>
          </div>
          <div class="ticket-form-wrapper">
            <div class="ticket-header nav-tabs nav border-0">
              <h4 class="title">Choose Your Ticket</h4>
            </div>
            <div class="tab-content">
              <div class="tab-pane fade show active" id="one-way">
                <form action="https://script.viserlab.com/viserbus/ticket/search" class="ticket-form row g-3 justify-content-center m-0">
                  <div class="col-md-6">
                    <div class="form--group">
                      <i class="las la-location-arrow"></i>
                      <select class="form--control select2" name="pickup">
                        <option value="">Pickup Point</option>
                        <option value="1" >Kansas</option>
                        <option value="2" >Dallas</option>
                        <option value="3" >Wichita</option>
                        <option value="4" >Emi Davenport</option>
                        <option value="5" >Echo Bass</option>
                      </select>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="form--group">
                      <i class="las la-map-marker"></i>
                      <select name="destination" class="form--control select2">
                        <option value="">Dropping Point</option>
                        <option value="1" >Kansas</option>
                        <option value="2" >Dallas</option>
                        <option value="3" >Wichita</option>
                        <option value="4" >Emi Davenport</option>
                        <option value="5" >Echo Bass</option>
                      </select>
                    </div>
                  </div>
                  <div class="col-md-12">
                    <div class="form--group">
                      <i class="las la-calendar-check"></i>
                      <input type="text" name="date_of_journey" class="form--control datepicker" placeholder="Departure Date" autocomplete="off">
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="form--group">
                      <button>Find Tickets</button>
                    </div>
                  </div>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="shape">
        <img src="assets/images/frontend/banner/6209144de6ed01644762189.png" alt="bg">
      </div>
    </section>
    <!-- Banner Section Ends Here -->

    <!-- Working Process Section Starts Here -->
    <section class="working-process padding-top padding-bottom">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6 col-md-10">
            <div class="section-header text-center">
              <h2 class="title">Get Your Tickets With Just 3 Steps</h2>
              <p>Have a look at our popular reason. why you should choose you bus. Just a Bus and get a ticket for your great journey. !</p>
            </div>
          </div>
        </div>
        <div class="row g-4 gy-md-5 justify-content-center">
          <div class="col-lg-4 col-md-6 col-sm-10">
            <div class="working-process-item">
              <div class="thumb-wrapper">
                <span>01</span>
                <div class="thumb">
                  <i class="las la-search"></i>                        </div>
              </div>
              <div class="content">
                <h4 class="title">Search Your Bus</h4>
                <p>Choose your origin, destination,Just choose a Bus journey dates and search for buses</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-10">
            <div class="working-process-item">
              <div class="thumb-wrapper">
                <span>02</span>
                <div class="thumb">
                  <i class="las la-ticket-alt"></i>                        </div>
              </div>
              <div class="content">
                <h4 class="title">Choose The Ticket</h4>
                <p>Choose your origin, destination,Just a Bus for your great journey dates and search for buses</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-10">
            <div class="working-process-item">
              <div class="thumb-wrapper">
                <span>03</span>
                <div class="thumb">
                  <i class="las la-money-bill-wave-alt"></i>                        </div>
              </div>
              <div class="content">
                <h4 class="title">Pay Bill</h4>
                <p>Choose your origin, destination,choose a Bus for your great journey dates and search for buses</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Working Process Section Ends Here -->
    <!-- Our Ameninies Section Starts Here -->
    <section class="amenities-section padding-bottom">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6 col-md-10">
            <div class="section-header text-center">
              <h2 class="title">Our Amenities</h2>
              <p>Have a look at our popular reason. why you should choose you bus.Just choose a Bus and get a ticket for your great journey!</p>
            </div>
          </div>
        </div>
        <div class="amenities-wrapper">
          <div class="amenities-slider">
            <div class="single-slider">
              <div class="amenities-item">
                <div class="thumb">
                  <i class="las la-wifi"></i>                        </div>
                <h6 class="title">Wifi</h6>
              </div>
            </div>
            <div class="single-slider">
              <div class="amenities-item">
                <div class="thumb">
                  <i class="las la-bed"></i>                        </div>
                <h6 class="title">Pillow</h6>
              </div>
            </div>
            <div class="single-slider">
              <div class="amenities-item">
                <div class="thumb">
                  <i class="las la-prescription-bottle"></i>                        </div>
                <h6 class="title">Water Bottle</h6>
              </div>
            </div>
            <div class="single-slider">
              <div class="amenities-item">
                <div class="thumb">
                  <i class="fas fa-wine-glass-alt"></i>                        </div>
                <h6 class="title">Soft Drinks</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Our Ameninies Section Ends Here -->
    <!-- Section Starts Here -->
    <section class="padding-bottom padding-top testimonial-section">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6 col-md-8">
            <div class="section-header text-center">
              <h2 class="title">Our Testimonials</h2>
              <p>Have a look at our popular reason. why you should choose you bus. Just choose a Bus and get a ticket for your great journey!</p>
            </div>
          </div>
        </div>
        <div class="row justify-content-center gy-5">
          <div class="col-lg-8 col-md-10">
            <div class="testimonial-wrapper">
              <div class="testimonial-slider">
                <div class="single-slider">
                  <div class="testimonial-item">
                    <div class="content">
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam iusto mollitia facere accusantium deleniti odit eius, amet doloribus fugit delectus doloremque! In, corrupti? Est, autem suscipit voluptatem rerum deserunt laudantium.</p>
                    </div>
                    <div class="thumb-wrapper">
                      <div class="thumb">
                        <img src="assets/images/frontend/testimonials/61f13ad31ec4d1643199187.jpg" alt="testimonials">
                      </div>
                      <h5 class="name">Parvin Akter</h5>
                    </div>
                  </div>
                </div>
                <div class="single-slider">
                  <div class="testimonial-item">
                    <div class="content">
                      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ullam iusto mollitia facere accusantium deleniti odit eius, amet doloribus fugit delectus doloremque! In, corrupti? Est, autem suscipit voluptatem rerum deserunt laudantium.</p>
                    </div>
                    <div class="thumb-wrapper">
                      <div class="thumb">
                        <img src="assets/images/frontend/testimonials/61f13ac0c23181643199168.jpg" alt="testimonials">
                      </div>
                      <h5 class="name">Sarmin Sultana</h5>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Section Ends Here -->
    <!-- Blog Section Starts Here -->
    <section class="blog-section padding-top padding-bottom">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-6 col-md-10">
            <div class="section-header text-center">
              <h2 class="title">Recent Blog Post</h2>
              <p>Have a look at our popular reason. why you should choose you bus. Just choose a Bus and get a ticket for your great journey. !</p>
            </div>
          </div>
        </div>
        <div class="row justify-content-center g-4">
          <div class="col-lg-4 col-md-6 col-sm-10">
            <div class="post-item">
              <div class="post-thumb">
                <img src="assets/images/frontend/blog/thumb_6210e4b6d132d1645274294.jpg" alt="blog">
              </div>
              <div class="post-content">
                <ul class="post-meta">
                  <li>
                    <span class="date"><i class="las la-calendar-check"></i>19 Feb 2022</span>
                  </li>
                </ul>
                <h4 class="title"><a href="blog/89/the-standard-lorem-ipsum-passage-used-since-the-1500s.html">The standard Lorem Ipsum passage, used since the 1500s</a></h4>
                <p>&quot;Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-10">
            <div class="post-item">
              <div class="post-thumb">
                <img src="assets/images/frontend/blog/thumb_62108d71dc2dc1645251953.jpg" alt="blog">
              </div>
              <div class="post-content">
                <ul class="post-meta">
                  <li>
                    <span class="date"><i class="las la-calendar-check"></i>19 Feb 2022</span>
                  </li>
                </ul>
                <h4 class="title"><a href="blog/88/lorem-ipsum-is-simply-dummy.html">Lorem Ipsum is simply dummy</a></h4>
                <p>Lorem  simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry&#039;s standard...</p>
              </div>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 col-sm-10">
            <div class="post-item">
              <div class="post-thumb">
                <img src="assets/images/frontend/blog/thumb_62108d54284f11645251924.jpg" alt="blog">
              </div>
              <div class="post-content">
                <ul class="post-meta">
                  <li>
                    <span class="date"><i class="las la-calendar-check"></i>19 Feb 2022</span>
                  </li>
                </ul>
                <h4 class="title"><a href="blog/87/why-do-we-use-it.html">Why do we use it?</a></h4>
                <p>Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature...</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Blog Section Ends Here -->
    <!-- Footer Section Starts Here -->
    <section class="footer-seciton">
      <div class="footer-top">
        <div class="container">
          <div class="row footer-wrapper gy-sm-5 gy-4">
            <div class="col-xl-4 col-lg-3 col-md-6 col-sm-6">
              <div class="footer-widget">
                <div class="logo">
                  <img src="assets/images/logoIcon/logo_2.png" alt="Logo">
                </div>
                <p>Delectus culpa laboriosam debitis saepe. Commodi earum minus ut obcaecati veniam deserunt est!</p>
                <ul class="social-icons">
                  <li>
                    <a href="https://www.facebook.com/"><i class="lab la-facebook-f"></i></a>
                  </li>
                  <li>
                    <a href="https://twitter.com/?lang=en"><i class="lab la-twitter"></i></a>
                  </li>
                  <li>
                    <a href="https://vimeo.com/log_in"><i class="lab la-vimeo"></i></a>
                  </li>
                  <li>
                    <a href="https://www.instagram.com/?hl=en"><i class="lab la-instagram"></i></a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6">
              <div class="footer-widget">
                <h4 class="widget-title">Useful Links</h4>
                <ul class="footer-links">
                  <li>
                    <a href="about-us.html">About</a>
                  </li>
                  <li>
                    <a href="faq.html">FAQs</a>
                  </li>
                  <li>
                    <a href="blog.html">Blog</a>
                  </li>
                  <li>
                    <a href="contact.html">Contact</a>
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-xl-2 col-lg-3 col-md-4 col-sm-6">
              <div class="footer-widget">
                <h4 class="widget-title">Policies</h4>
                <ul class="footer-links">
                  <li>
                    <a href="policy/69/privacy-policy.html">Privacy Policy</a>
                  </li>
                  <li>
                    <a href="policy/71/terms-and-conditions.html">Terms and Conditions</a>
                  </li>
                  <li>
                    <a href="policy/90/ticket-policies.html">Ticket Policies</a>
                  </li>
                  <li>
                    <a href="policy/102/refund-policy.html">Refund Policy</a>
                  </li>

                </ul>
              </div>
            </div>
            <div class="col-xl-3 col-lg-3 col-md-4 col-sm-6">
              <div class="footer-widget">
                <h4 class="widget-title">Contact Info</h4>
                <ul class="footer-contacts">
                  <li>
                    <i class="las la-map-pin"></i> Bengla Road Suite Dhaka 1209
                  </li>
                  <li>
                    <i class="las la-phone-volume"></i> <a href="tel:+44 45678908"> +44 45678908</a>
                  </li>
                  <li>
                    <i class="las la-envelope"></i> <a href="https://script.viserlab.com/cdn-cgi/l/email-protection#a3c6dbc2ced3cfc6e3c4cec2cacf8dc0ccce"> <span class="__cf_email__" data-cfemail="1d78657c706d71785d7a707c7471337e7270">[email&#160;protected]</span></a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Footer Section Ends Here -->


    <!-- cookies default start -->
    <div id="cookiePolicy" class="cookies-card bg--default radius--10px text-center">
      <div class="cookies-card__icon">
        <i class="fas fa-cookie-bite"></i>
      </div>
      <p class="mt-4 cookies-card__content">
        <font face="Exo, sans-serif"><span style="font-size: 18px;">We may use cookies or any other tracking technologies when you visit our website, including any other media form, mobile website, or mobile application related or connected to help customize the Site and improve your experience.</span></font><br>        <a href="cookie/details.html" target="_blank">learn more</a>
      </p>
      <div class="cookies-card__btn mt-4">
        <a href="#" name="cookieAccept" class="cookies-btn">Allow</a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class HomeView extends Vue {}
</script>
