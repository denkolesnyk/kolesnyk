---
title: Contact
slug: contact
---
Afin de prendre contact avec M. Kolesnyk veuillez utiliser la forme ci-dessous :

<form name="contact" method="POST" data-netlify-recaptcha="true" data-netlify="true">
    <input type="hidden" name="form-name" value="contact" />
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Name"></label>
        <div class="col-md-4">
            <input id="contact-form-name" name="Name" type="text" placeholder="Nom" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Email"></label>
        <div class="col-md-4">
            <input id="contact-form-email" name="Email" type="email" placeholder="Courriel" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Subject"></label>
        <div class="col-md-4">
            <input id="contact-form-subject" name="Subject" type="text" placeholder="Sujet" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <!-- Textarea -->
    <div class="form-group">
        <label class="col-lg-2 control-label" for=""></label>
        <textarea class="form-control" id="contact-form-message" name="Message" placeholder="Votre message" rows="8"></textarea>
    </div>
     <div data-netlify-recaptcha="true"></div>
    <!-- Button -->
    <div class="form-group">
        <button type="submit" value="Submit" id="Form-submit">Envoyer</button>
    </div>
</form>

Vous pouvez également le contacter via Twitter [@denkolesnyk](https://twitter.com/denkolesnyk)