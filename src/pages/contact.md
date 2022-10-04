---
title: Get in touch
metaDescription: This is a sample meta description. If one is not present in your page/post's front matter, the default metadata.desciption will be used instead.
section: contact
date: 2018-01-01
permalink: /contact/index.html
cta: false
eleventyNavigation:
  key: Contact
  order: 3
---

<section id="contact-form" class="contact-form wf-section">
    <div class="w-container">
        <p>Ready to talk?&nbsp;Let's schedule a discovery call to get to know you and what you're looking for.</p>
        <div class="w-embed w-script">
            <!--  Calendly inline widget begin  -->
            <div class="calendly-inline-widget" data-url="https://calendly.com/secretariatmedia/30min" style="position: relative;min-width:320px;height:1030px;" data-processed="true"><div class="calendly-spinner"><div class="calendly-bounce1"></div><div class="calendly-bounce2"></div><div class="calendly-bounce3"></div></div><iframe src="https://calendly.com/secretariatmedia/30min?embed_domain=www.secretariatmedia.com&amp;embed_type=Inline" width="100%" height="100%" frameborder="0"></iframe></div>
            <script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async=""></script>
            <!--  Calendly inline widget end  -->
        </div>
    </div>
</section>

<section id="contact-form" class="contact-form wf-section">
    <div class="w-container">
        <h2 class="heading">Contact Us</h2>
        <p>You can use the form below to get in touch with us.</p>
        {% include "components/contact-form.njk" %}
</section>