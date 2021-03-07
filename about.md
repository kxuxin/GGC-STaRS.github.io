---
layout: about
title: About
permalink: /about/
photos:
- 12915108384_1a98518cfa_o.jpg
- 16625184114_f70749312b_b.jpg
- 16627102103_1d05c23e64_b.jpg
- 17061099369_a1e34de66b_b.jpg
- 17247305655_b9ae4e3dbf_b.jpg
- 18378901762_6b8003daf3_o.jpg
- 23833278995_e661c76950_o.jpg
- Biology Food Burn Calorie Lab Biology Food Burn Calorie Ct_GGC2158.jpg
- Biology Food Burn Calorie Lab Biology Food Burn Calorie Ct_GGC2167.jpg
- Candid Chemistry Images for H12841578704_458defb39e_o.jpg
- Candid Chemistry Images for H16776090625_f4ab55cca2_o.jpg
- Candid Chemistry Images for H44621689285_a108f29202_o.jpg
- Game of Drones Fall 2019_GGC9879.jpg
- GGC5524.JPG
- GGC5579.JPG
- GGC5750.JPG
- GGC5804.JPG
- GGC9281.JPG
- Jesse Merida 3D Face masks_GGC5642.JPG
- Mai Yin Tsoi Teaching Chem _GGC7491.JPG
- Screenshot (48).png
- Service learning Interns SST_GGC4759.JPG
- SST Students and Faculty _GGC6848.jpg
- Strickland Lab 1.jpg
- Strickland Lab 2.jpg
- Strickland Lab 3.jpg
- Strickland Lab 4.jpg
- TAP Event Fall 2019_GGC2975.jpg
- TAP Event Fall 2019_GGC3446.jpg
- TAP Event Fall 2019Tech Ambassador Program TAP_GGC1558.jpg
- TAP Event Fall 2019Tech Ambassador Program TAP_GGC1644.jpg
- Tech Ambassador Program TAP_GGC1439.JPG
---

The Science Technology and Reseach Symposium (STaRS) is organized by the School of Science and Technology at Georgia Gwinnett College every spring. The purpose of this event is to promote science, math, and technology for our STEM students, and to provide opportunities to showcase the scientific research and other STEM activities that take place at GGC. This year’s all virtual event will take place on **Thursday April 8th, 2021** from **12:00 noon to 3:00 p.m**.  The purpose of this event is to promote science, math, and technology for our STEM students, and to provide opportunities to showcase the scientific research and other STEM activities that take place at GGC. 


![SST collage](/assets/images/sst-image-fb.jpg "A collage of SST faculty and students")

One of the main attractions for our undergraduates attending STaRS is the Graduate and Professional School Fair in which representatives from regional graduate and professional schools provide admissions and program information for students who seek to submit competitive applications.  Many of our students pursue post-graduate degrees after GGC, and we believe that they will be excited to hear about the Graduate Programs offered at your institution. Although the format will be a little different this year due to the current pandemic, this offers a unique opportunity to host representatives that would otherwise be limited by geographical distance.  

The School of Science and Technology (SST) at GGC is creating a diverse community of STEM graduates. SST offers programs in Biology, Chemistry, Information Technology, Mathematics, Exercise Science, and Environmental Science and has a unique and diverse student population (32% Black or African-American, 19% Hispanic, and 14% Asian), with 54% males and 46% females.  About 30% of SST students are the first in their families to go to college.  Nearly all STEM students participate in STaRS and the event is open to other GGC students as well, with an estimated 3,000 GGC students in attendance.  

Thus, your participation at STaRS is a great opportunity for you to establish a strong presence on GGC's campus and market your programs to future GGC STEM graduates.  We invite you to take advantage of this opportunity to engage our diverse student body, raise their level of interest, and introduce them to your programs. 
To help defray the costs of the event, we are asking for a modest Registration Fee of $50.  The fee will grant you access to your own virtual room to interact with our many enthusiastic GGC students who are interested in your graduate programs. To register your institution, visit this link: https://georgia-gwinnett-college-foundation-inc.square.site/product/grad-professional-other-attendee/38?cs=true&cst=custom 

If you have any questions about the STaRS Graduate & Professional School Fair, please contact Dr. Sharon Keller (skeller6@ggc.edu). 
 
We hope to see you in April! 


  <div class="project_pictures">
    <div id="slideshow">
      {% for photo in page.photos %}
      <div class="pictures">
        <a  id="lightgallery" href="/assets/images/slideshow/{{ photo }}">
          <img src="/assets/images/slideshow/{{ photo }}">
        </a>
      </div>

      {% endfor %}
    </div>
  </div>
  
<!-- lightgallery -->
  <script src="https://cdn.jsdelivr.net/lightgallery/1.3.7/js/lightgallery.min.js"></script>
  <script src="https://cdn.jsdelivr.net/g/lg-zoom"></script>

  <script type="text/javascript">
    $(document).ready(function() {      
      // Slideshow setup
      $("#slideshow > div:gt(0)").hide();

      setInterval(function() {
        $('#slideshow > div:first')
          .fadeOut(1000)
          .next()
          .fadeIn(1000)
          .end()
          .appendTo('#slideshow');
      }, 3000);

      // LightGallery
      $("body").lightGallery({
	zoom: true,
	selector: 'a#lightgallery',
	selectWithin: 'body'
      });
    });
  </script>



 
