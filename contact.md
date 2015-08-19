---
layout: page
title: Contact
permalink: /contact/
---
<div class="narrow">
    <form action="//formspree.io/maxmumford@gmail.com" method="POST" id="contact">
        <input type="hidden" name="_next" value="{{site.url}}/thanks" />
        <input type="text" name="_gotcha" style="display:none" />

            <div class="form-group">
            <label>Name</label>
            <input type="text" class="form-control" name="name" />
        </div>
        <div class="form-group">
            <label>Email address</label>
            <input type="text" class="form-control" name="email" />
        </div>
        <div class="form-group">
            <label>Phone</label>
            <input type="text" class="form-control" name="phone" />
        </div>
        <div class="form-group">
            <label>Message</label>
            <textarea name="message" class="form-control" rows="3" placeholder="Interested in working together? Want more information?"></textarea>
        </div>
        <div class="spacer"></div>
        <div class="form-group center">
                <input type="submit" value="Send" class="btn btn-primary">
        </div>
    </form>
</div>
