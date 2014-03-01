---
layout: page
permalink: /rsvp/
title: RSVP
modified: 2014-02-20
locale: en
---
<script src="{{ site.url }}/assets/js/vendor/h5f.min.js"></script>

<form markdown="0" action="https://docs.google.com/forms/d/1_K5UATic7NrNF3kJKgF0G6kb-raqZLQBkR9AEtmf5fM/formResponse" method="POST" id="ss-form" target="_self" onsubmit="">
<label for="entry_1006834607">
{{site.rsvp[page.locale].name}}:
<input type="text" name="entry.1006834607" value="" class="ss-q-short" id="entry_1006834607" dir="auto" aria-label="Full name  " aria-required="true" required="" >
</label>
<label for="entry_1023119450">
{{site.rsvp[page.locale].email}}: <input type="email" name="entry.1023119450" value="" class="ss-q-short" id="entry_1023119450" dir="auto" aria-label="Email  Email address invalid" aria-required="true" required="" title="Email address invalid">
</label>

<label>{{site.rsvp[page.locale].coming_q}}</label>
<label class="radio" for="entry_1142779736">
<input type="radio" name="entry.1142779736" value="Coming" id="group_1142779736_1" role="radio" class="ss-q-radio valid" aria-label="Coming" required="" aria-required="true" checked>{{site.rsvp[page.locale].coming}}
</label>
<label class="radio" for="entry_1142779736">
<input type="radio" name="entry.1142779736" value="Not coming" id="group_1142779736_2" role="radio" class="ss-q-radio valid" aria-label="Not coming" required="" aria-required="true">{{site.rsvp[page.locale].not_coming}}
</label>

<label for="entry_1399220995">
{{site.rsvp[page.locale].guest_number}} <input type="number" name="entry.1399220995" value="" class="ss-q-short" id="entry_1399220995" dir="auto" aria-label="Number of guest including you  This must be a number greater or equal to 0" aria-required="true" required="" step="any" min="0.0" aria-valuemin="0.0" title="This must be a number greater or equal to 0">
</label>
<label for="entry_1124372142">
{{site.rsvp[page.locale].address}}:
<textarea name="entry.1124372142" rows="8" cols="0" class="ss-q-long valid" id="entry_1124372142" dir="auto" aria-label="Address This is to send you your invitation "></textarea>
</label>
<label for="entry_761390467">
{{site.rsvp[page.locale].tel}}: <input type="text" name="entry.761390467" value="" class="ss-q-short valid" id="entry_761390467" dir="auto" aria-label="Phone number Just in case " title="">
</label>

<input type="hidden" name="draftResponse" value="[]">
<input type="hidden" name="pageHistory" value="0">

<div style="width:100%;text-align:center; margin-top:10px;">
<input type="submit" class="btn"></input>
</div>

</form>

<script type="text/javascript">H5F.setup(document.getElementById('ss-form'));</script>
