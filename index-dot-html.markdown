---
title: index.html
date: 2017-06-18 23:34:00 Z
---

---
layout: start
---


<section>
         <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading">The Company</h2>
                    <hr class="primary">
                </div>
            </div>
        </div>

           <div class="container-fluid">

    <div class="col-sm-6 padd-l" >
<p class="font-match intro-p"><strong>Campaign Storage</strong>
- invented at Los Alamos National Laboratory - is a radically new software defined storage (SDS) technology to manage tiers of storage.
It provides tools for massive parallel data movement between the new low cost, industry standard campaign storage tier tiers with premium storage
for performance or availability. Beyond moving the data, campaign storage offers new tools to execute data management policies and archiving,
including transparent integration with HSM frameworks and 3rd party policy managers.</p>

<p class="font-match intro-p">
Campaign Storage, LLC focusses on bringing this to market as a product.</p>

<p class="font-match intro-p">
Campaign Storage stands out from other solutions by building on industry standard object storage systems many of which are supported.</p>

<p class="font-match intro-p">
Unlike archiving solutions, metadata is stored using ZFS technology, for ultimate reliability and flexibility with storage management.</p>
  </div>

  <div class="col-sm-6 padd-l" >&nbsp;<img src="img/waterfall.jpg" alt="" width="100%" height="auto"></div>

  </div>

    </section>

<section id="portfolio" style="padding-top: 55px;">
 <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center">
                    <h2 class="section-heading">Technology</h2>
                    <hr class="primary">
                </div>
            </div>
        </div>

       <div class="container-fluid">

    <div class="col-sm-6 padd-l">
 <h3>Campaign Storage for Lustre&reg; HSM</h3>
        <p class="text-muted font-match">You can now participate in the beta program
     for the <a href="docs/CS-Lustre-HSM-2017-03-17.pdf">Campaign Storage Lustre&reg; HSM</a> release,
     which includes <a href="http://www.spectralogic.com"> Spectra
     Logic </a>  Black Pearl tape object stores.
     <br>For more information, just drop us an email at  <a href="mailto:lustrehsm@campaignstorage.com">lustrehsm@campaignstorage.com</a>
</p>

    </div>

                      <div class="col-sm-6 padd-l" >

                        <h3>Join the channel</h3>

                          <p class="text-muted font-match">We
                          invite vendors to contact us to discuss
                          integration of our software with their
                          hardware systems or object storage systems
                          to create integrated solutions. A few of the
                          possibilities for hardware are described in
                          our <a href="https://docs.google.com/document/d/1sdR_Swl-KvIy_tdm3Q-ZfMdNBhIAkHV1bXkUgSjNElM/pub">Campaign
                          Storage Hardware (Peter Braam)</a> whitepaper.
                         <br>Write to us at <a href="mailto:partners@campaignstorage.com">partners@campaignstorage.com</a></p>


           </div>
       </div>
                  <div class="container-fluid">


               <div class="col-sm-6 padd-l" >
                   <h3>Campaign Storage Industry Steering Group</h3>
                        <p class="text-muted font-match">Campaign
                        Storage, LLC and Los Alamos National
                        Laboratory have organized an industry steering
                        group for the platform. Please drop us an
                        email if you wish to be invited to the
                        upcoming meetings for Americas, European and
                        Asia Pacific time zones at
                            <a href="mailto:steeringgroup@campaignstorage.com">steeringgroup@campaignstorage.com</a>
                        </p>
               </div>

           <div class="col-sm-6 padd-l" >

                        <h3>Technology Background</h3>
                        <p class="text-muted font-match">
                            <a href="https://drive.google.com/open?id=0BxmMukc1qysObUpHNlNfcnhEMU0">Campaign Storage White Paper (Peter Braam)</a>
                            <br>
                            <a href="https://drive.google.com/open?id=0BxmMukc1qysObkZKUGNyNEtIdzA">Campaign Storage Technical Paper (Peter Braam &amp; Dave Bonnie - LANL)</a>

</p>

           </div>


  </div><!--container-fluid-->

    </section>

    <section class="bg-primary" id="about">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 col-lg-offset-2 text-center">
                    <h2 class="section-heading">About Us</h2>
                    <hr class="light">
                    <p class="text-center font-match cust-abt">Campaign Storage was founded in 2016 by Peter Braam and Nathan Thompson, two leaders in the storage industry.  We operate a small team out of Boulder, CO.  The company announced its first product at Super Computing 2016. It has closed a second round of seed funding.</p>

                </div>
            </div>
        </div>
    </section>


    <section id="news">
        <div class="container">
            <div class="row">
                    <h2 class="section-heading text-center">News</h2>
                    <hr class="prinmary text-center">
                    <div class="col-md-10 col-md-offset-2">
                    <ul class="post-list">
                    {% for post in site.posts limit:3 %}
                      <li>
                        {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
                        <span class="post-meta">{{ post.date | date: date_format }} » &nbsp;&nbsp;<a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a></span></li>
                    {% endfor %}
                  </ul>
                    <p class="font-match"><a href="{{ "/blog/" | relative_url }}">Read More &rArr;</a></p>
                  </div>
            </div>
        </div>
    </section>


  <section id="contact">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 col-lg-offset-2 text-center">
                    <h2 class="section-heading">Let's Get In Touch!</h2>
                    <hr class="primary">
                    <p class="text-center font-match">Ready to start your next project with us? That's great! Give us a call or send us an email and we will get back to you as soon as possible!</p>
                </div>
                <div class="col-lg-4 col-lg-offset-2 text-center">
                    <i class="fa fa-phone fa-3x sr-contact"></i>
                    <p class="font-match">+1 720-317-0170</p>
                </div>
                <div class="col-lg-4 text-center">
                    <i class="fa fa-envelope-o fa-3x sr-contact"></i>
                    <p class="font-match"><a  class="link" href="mailto:info@campaignstorage.com">info@campaignstorage.com</a></p>

                </div>

            </div>

        </div>
    </section>
