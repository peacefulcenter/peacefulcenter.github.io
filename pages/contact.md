---
header_title: Contact Us
# address_line_one: 1234 Philanthropy Rd.
# address_line_two: 
# city: Bend
# state: OR
# zip: 97701
# phone: TBD
# fax: TBD
email: thepeacefulcenter@outlook.com
layout: contact
permalink: /:basename/
---

<!-- Your entries above cannot contain colons -->
<!-- The only colon should be after the variable name (e.g. city:) -->
<!-- The colon is used to separate the variable name from the variable content -->
<!-- The exception is the second colon in the permalink field (e.g. permalink: /:basename/) -->
<!-- BAD -->
<!-- address_line_one: SomeBank, ATTN: Chris Smith -->
<!-- GOOD -->
<!-- address_line_one: SomeBank, ATTN Chris Smith -->
<section id="three">
    <div id="formkeep-embed" data-formkeep-url="https://formkeep.com/p/75d5dd1ed687edbcfff4c98f69db3917?embedded=1"></div>        
</section>

<script type="text/javascript" src="https://pym.nprapps.org/pym.v1.min.js"></script>
<script type="text/javascript" src="https://cdn.formkeep.com/formkeep-embed.js"></script>

<!-- Get notified when the form is submitted, add your own code below: -->
<script>
const formkeepEmbed = document.querySelector('#formkeep-embed')

formkeepEmbed.addEventListener('formkeep-embed:submitting', _event => {
  console.log('Submitting form...')
})

formkeepEmbed.addEventListener('formkeep-embed:submitted', _event => {
  console.log('Submitted form...')
})
</script>