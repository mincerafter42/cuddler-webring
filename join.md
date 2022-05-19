---
layout: html
title: How to Join the Cuddler Webring
---
# Join the Cuddler Webring
## Criteria to join
- You should love cuddles, and have a personal webpage (that's what this webring is for, after all :)  
  The webpage you add to the webring doesn't have to be your website's index page; it could be a cuddle-themed page or a webring hub, for examples.
- If your website has any NSFW content (including gore), it must be clearly marked as such.
- Your website should have no hate speech or bigotry.
- Your website should not be advertisement-focused.

<small>It is impossible to enumerate everything that is not allowed. For this reason, we (the webmasters) reserve the right to remove a site if we feel it is outside of our own personal bounds.</small>

## Add yourself to the members list
Add a unique slug, your webpage's name, and your webpage's URL to [the members list on GitHub]({{site.github_repo_url}}/blob/main/_data/members.csv) in a pull request.  
Pull requests can also be used to change your existing entry or delete your entry.
<details>
<summary>If you don't have a GitHub account, fill out this form instead:</summary>
<form name=signup method=POST data-netlify=true netlify-honeypot=bot>
<div hidden><label>Leave this blank unless you're spam <input name=bot></label></div>
<label>Slug <input name=slug pattern="[0-9a-z](?:-?[0-9a-z])*" required></label> (ASCII lowercase letters, digits, and hyphen-minuses)<br>
<label>Name <textarea name=name></textarea></label><br>
<label>URL <input name=url type=url></label><br>
<input type=submit>
</form>
If you're editing your existing entry, make sure to use the same slug. If you're deleting your existing entry, leave the URL field blank.
</details>

## Add links on your webpage
Once you're on the members list, add links on your webpage to <b>{{'/YOUR-SLUG/next'|absolute_url}}</b> and <b>{{'/YOUR-SLUG/previous'|absolute_url}}</b>, replacing <b>YOUR-SLUG</b> with the slug you chose.  
Feel free to include a link to <b>{{'/'|absolute_url}}</b> as well.  
Check if [the `<aside>` element](https://html.spec.whatwg.org/dev/sections.html#the-aside-element) is right for you.
