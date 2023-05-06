---
title: "Newsletter"
date: "2023-03-20"
---

### Subscribe for newsletter

<div class="form">
    <form name="contactform" method="POST" action="thanks.html">
    <?php include 'form.php';?>
        <div class="form-row">
            <div class="form-group col-lg-6" id="mail">
                <input type="email" class="form-control" placeholder="Email" name="email" data-rule="email" data-msg="Please enter a valid email">
            </div>
        </div>
        <div class="text-center"><button type="submit"  id="button" name="submit" title="Send Message">Subscribe now</button></div>
    </form>
</div>
