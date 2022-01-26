Responsive Chat built with Bootstrap 5. Many variants of the chat UI - mobile app, messages box, desktop widget and more.

Check out [Bootstrap Chat Documentation](https://mdbootstrap.com/docs/standard/extended/chat/) for detailed instructions & even more examples.


## Basic example


![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/basic.png)

```html
<section style="background-color: #eee;">
  <div class="container py-5">

    <div class="row d-flex justify-content-center">
      <div class="col-md-8 col-lg-6 col-xl-4">

        <div class="card" id="chat1" style="border-radius: 15px;">
          <div
            class="card-header d-flex justify-content-between align-items-center p-3 bg-info text-white border-bottom-0"
            style="border-top-left-radius: 15px; border-top-right-radius: 15px;">
            <i class="fas fa-angle-left"></i>
            <p class="mb-0 fw-bold">Live chat</p>
            <i class="fas fa-times"></i>
          </div>
          <div class="card-body">

            <div class="d-flex flex-row justify-content-start mb-4">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava1-bg.webp" alt="avatar 1"
                style="width: 45px; height: 100%;">
              <div class="p-3 ms-3" style="border-radius: 15px; background-color: rgba(57, 192, 237,.2);">
                <p class="small mb-0">Hello and thank you for visiting MDBootstrap. Please click the video below.</p>
              </div>
            </div>

            <div class="d-flex flex-row justify-content-end mb-4">
              <div class="p-3 me-3 border" style="border-radius: 15px; background-color: #fbfbfb;">
                <p class="small mb-0">Thank you, I really like your product.</p>
              </div>
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava2-bg.webp" alt="avatar 1"
                style="width: 45px; height: 100%;">
            </div>

            <div class="d-flex flex-row justify-content-start mb-4">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava1-bg.webp" alt="avatar 1"
                style="width: 45px; height: 100%;">
              <div class="ms-3" style="border-radius: 15px;">
                <div class="bg-image">
                  <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/screenshot1.webp"
                    style="border-radius: 15px;" alt="video">
                  <a href="#!">
                    <div class="mask"></div>
                  </a>
                </div>
              </div>
            </div>

            <div class="d-flex flex-row justify-content-start mb-4">
              <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-chat/ava1-bg.webp" alt="avatar 1"
                style="width: 45px; height: 100%;">
              <div class="p-3 ms-3" style="border-radius: 15px; background-color: rgba(57, 192, 237,.2);">
                <p class="small mb-0">...</p>
              </div>
            </div>

            <div class="form-outline">
              <textarea class="form-control" id="textAreaExample" rows="4"></textarea>
              <label class="form-label" for="textAreaExample">Type your message</label>
            </div>

          </div>
        </div>

      </div>
    </div>

  </div>
</section>
```

CSS

```css
#chat1 .form-outline .form-control~.form-notch div {
  pointer-events: none;
  border: 1px solid;
  border-color: #eee;
  box-sizing: border-box;
  background: transparent;
}

#chat1 .form-outline .form-control~.form-notch .form-notch-leading {
  left: 0;
  top: 0;
  height: 100%;
  border-right: none;
  border-radius: .65rem 0 0 .65rem;
}

#chat1 .form-outline .form-control~.form-notch .form-notch-middle {
  flex: 0 0 auto;
  max-width: calc(100% - 1rem);
  height: 100%;
  border-right: none;
  border-left: none;
}

#chat1 .form-outline .form-control~.form-notch .form-notch-trailing {
  flex-grow: 1;
  height: 100%;
  border-left: none;
  border-radius: 0 .65rem .65rem 0;
}

#chat1 .form-outline .form-control:focus~.form-notch .form-notch-leading {
  border-top: 0.125rem solid #39c0ed;
  border-bottom: 0.125rem solid #39c0ed;
  border-left: 0.125rem solid #39c0ed;
}

#chat1 .form-outline .form-control:focus~.form-notch .form-notch-leading,
#chat1 .form-outline .form-control.active~.form-notch .form-notch-leading {
  border-right: none;
  transition: all 0.2s linear;
}

#chat1 .form-outline .form-control:focus~.form-notch .form-notch-middle {
  border-bottom: 0.125rem solid;
  border-color: #39c0ed;
}

#chat1 .form-outline .form-control:focus~.form-notch .form-notch-middle,
#chat1 .form-outline .form-control.active~.form-notch .form-notch-middle {
  border-top: none;
  border-right: none;
  border-left: none;
  transition: all 0.2s linear;
}

#chat1 .form-outline .form-control:focus~.form-notch .form-notch-trailing {
  border-top: 0.125rem solid #39c0ed;
  border-bottom: 0.125rem solid #39c0ed;
  border-right: 0.125rem solid #39c0ed;
}

#chat1 .form-outline .form-control:focus~.form-notch .form-notch-trailing,
#chat1 .form-outline .form-control.active~.form-notch .form-notch-trailing {
  border-left: none;
  transition: all 0.2s linear;
}

#chat1 .form-outline .form-control:focus~.form-label {
  color: #39c0ed;
}

#chat1 .form-outline .form-control~.form-label {
  color: #bfbfbf;
}
```

## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)




## More examples

[Simle Chat Application:
![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/simple.png)](https://mdbootstrap.com/docs/standard/extended/chat/#section-2)

[Chat window:
![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/big.png)](https://mdbootstrap.com/docs/standard/extended/chat/#section-3)

[Awesome Chat Messages Box:
![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/awesome.png)](https://mdbootstrap.com/docs/standard/extended/chat/#section-4)

[Chat window with gradient background:
![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/gradient.png)](https://mdbootstrap.com/docs/standard/extended/chat/#section-5)

[Chat window with colorful background:
![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/colorful.png)](https://mdbootstrap.com/docs/standard/extended/chat/#section-6)

[Collapsible Chat App:
![Bootstrap 5 Chat](https://mdbootstrap.com/img/Marketing/github/chat/collapsible.png)](https://mdbootstrap.com/docs/standard/extended/chat/#section-7)

___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>  
</ul>

