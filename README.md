<p align="center">
  <img src="https://www.eweek.com/wp-content/uploads/2020/10/Facebook-bug-bounty-1088x725-2.png" alt="Facebook Bug Bounty" width="300" />
</p>

# Facebook Bug bounty WriteUps


### Bugs

- [ImageTragick](#imagetragick)
- [XSS](#xss)
- [CSRF](#csrf)
- [SSRF](#ssrf)
- [Logic](#logic)
- [Race Conditions](#race-conditions)
- [Rate Limits](#rate-limits)
- [Open Redirect](#open-redirect)
- [Clickjacking](#clickjacking)
- [Object Reference](#object-reference)
- [Privacy | Spam](#privacy-spam)
- [Page Roles](#page-roles)
- [Facebook Ads](#facebook-ads)
- [Facebook Groups](#facebook-groups)
- [Phone number](#phone-number)
- [Email address](#email-address)
- [IP address](#ip-address)
- [Symlink Attack](#symlink-attack)
- [Accellion’s Secure File Transfer](#accelions-secure-file-transfer)
- [XXE](#xxe)
- [LFI](#lfi)
- [SQL Injection](#sqli)
- [Jekins](#jenkins)
- [API](#api)
- [GraphQL](#graphql)
- [FQL](#fql)
- [Login Nonces](login-nonces)
- [OAuth](#oauth)
- [Instagram](#instagram)
- [Signal](#signal)
- [Slingshot](#slingshot)
- [Moments](#moments)
- [Moves](#xxe)
- [WhatsApp](#whatspapp)

###  ImageTragick
* http://4lemon.ru/2017-01-17_facebook_imagetragick_remote_code_execution.html

### XSS
* http://ameeras.me/Instagram-Reflected-XSS-in-Link-Shim/
* https://whitton.io/articles/xss-on-facebook-via-png-content-types/
* http://philippeharewood.com/ability-to-upload-html-via-srt-caption-files-for-facebook-videos/ 
* http://www.breaksec.com/?p=5713
* http://www.nirgoldshlager.com/2013/01/another-stored-xss-in-facebookcom.html
* https://nealpoole.com/blog/2011/03/xss-vulnerability-in-facebook-translations/
* https://nealpoole.com/blog/2011/08/lessons-from-facebooks-security-bug-bounty-program/
* http://paulosyibelo.blogspot.com/2014/07/the-unseen-facebook-bug-bounty-2014-x.html
* https://prakharprasad.com/facebook-friendfeed-stored-xss/
* http://medu554.blogspot.com/2014/02/stored-xss-on-atlassolutions-facebook.html
* http://blog.ptsecurity.com/2013/10/a-story-about-xss-on-facebook.html
* https://www.youtube.com/watch?v=NQOK9-OXwsc (* http://pastebin.com/raw.php?i=cuYRhM71) 
* http://www.websecresearch.com/2014/02/facebooks-boltpeterscom-configuration.html
* http://nbsriharsha.blogspot.in/2014/03/finally-facebook-hunted.html
* https://whitton.io/articles/content-types-and-xss-facebook-studio/
* http://en.internetwache.org/facebook-fixes-minor-issues-02-05-2014/
* http://silentzzz.blogspot.com/2007/11/facebook-xss-vulnerability.html
* http://habrahabr.ru/company/pt/blog/247709/
* https://web.archive.org/web/20120416034642/* http://gill.is/2012/04/11/new_website
* http://www.paulosyibelo.com/2015/12/facebooks-moves-oauth-xss.html
* https://dr4cun0.com/blog/stored-xss-at-parse/
* https://twitter.com/opnsec/status/855076273395204097

### CSRF
* http://www.breaksec.com/?p=6192 (* https://vimeo.com/65453658)
* http://www.sneaked.net/invisible-arbitrary-csrf-profile-picture-upload-in-facebook
* http://pyx.io/blog/facebook-csrf-leading-to-full-account-takeover
* http://josipfranjkovic.blogspot.com/2013/11/facebook-bug-bounty-secondary-damage.html
* http://ceukelai.re/?p=35
* http://amolnaik4.blogspot.com/2012/08/facebook-csrf-worth-usd-5000.html
* https://web.archive.org/web/20160110053958/* http://www.dan-melamed.com/2013/06/hacking-any-facebook-account-exploit-poc.html
* http://www.paulosyibelo.com/2015/01/facebooks-oculus-exploiting.html
* http://blog.mazinahmed.net/2015/06/facebook-messenger-multiple-csrf.html
* https://whitton.io/articles/messenger-site-wide-csrf/
* http://philippeharewood.com/facebookmarketingdevelopers-com-proxies-csrf-quandry-and-api-fun/
* https://pouyadarabi.blogspot.com/2015/04/bypass-facebook-csrf.html
* https://pouyadarabi.blogspot.com/2016/05/how-i-bypassed-facebook-csrf-in-2016.html
* http://niyaax9.blogspot.com/2016/04/facebook-csrf-adding-welcome-notes-to.html
* https://medium.com/@zahidali_93675/cross-site-request-forgery-in-facebook-86087201d8c

### SSRF
 * https://dr4cun0.com/blog/ssrf-at-update-subscription-menu/

### Logic
* http://www.nirgoldshlager.com/2013/01/how-i-hacked-facebook-employees-secure.html
* http://pwndizzle.blogspot.in/2014/07/breaking-facebooks-text-captcha.html
* http://bugbountypoc.com/business-logic-flaw-facebook-poc/
* http://philippeharewood.com/edit-the-facebook-album-order-of-any-user/
* http://bugbountypoc.com/missing-authorization-check-in-pages-manager/
* https://immukul.blogspot.in/2017/04/facebook-bypassing-prohibit-embedding.html
* https://www.youtube.com/watch?v=Qu_A_s0LLbs
* https://www.youtube.com/watch?v=jxH1yyhCe_k
* https://www.youtube.com/watch?v=YFmvlInx4IQ
* https://www.youtube.com/watch?v=j_KiiiYpl4w
* http://www.aryansinha.com/2017/08/facebook-checkpoint-flaw.html

### Race Conditions
* https://www.josipfranjkovic.com/blog/race-conditions-on-web
* http://josipfranjkovic.blogspot.com/2015/04/race-conditions-on-facebook.html

### Rate Limits

* http://www.anandpraka.sh/2016/03/how-i-could-have-hacked-your-facebook.html
* http://arunsureshkumar.me/index.php/2016/04/24/facebook-account-take-over/
* http://xss001.blogspot.in/2016/05/instagram-account-takeover.html
* http://techmedia.com.ng/2016/05/21/bug-hunter-dislcoses-way-hack-instagram-accounts-facebook/
* http://www.kieranclaessens.be/uncategorized/facebook-text-message-actions-pincode-bruteforce/

### Open Redirect ($500+)

* http://thekaitokid.blogspot.com/2014/10/multiple-open-redirection.html
* http://mreagle0x.blogspot.com/2014/11/bypassing-facebook-linkshim-filtration.html
* http://arulxtronix.blogspot.in/2013/08/facebook-open-url-redirectors-2013.html
* http://www.vulnerability-lab.com/get_content.php?id=975
* http://yassineaboukir.com/blog/how-i-discovered-a-1000-open-redirect-in-facebook/

### Clickjacking
* http://codegrudge.blogspot.in/2015/03/how-i-got-5000-from-facebook-bugbounty.html
* http://www.paulosyibelo.com/2015/03/facebook-bug-bounty-clickjacking.html
* http://www.lachisterablanca.com/2014/02/bypass-de-la-proteccion-contra.html

### Object Reference ($12500+)

* http://www.anandpraka.sh/2014/11/hacking-facebookcomthanks-posting-on.html
* http://blog.fin1te.net/post/53949849983/hijacking-a-facebook-account-with-sms
* https://web.archive.org/web/20130903203919/* http://arulxtronix.blogspot.com/2013/09/delete-any-photo-from-facebook-by.html
* https://whitton.io/articles/removing-covers-images-on-friendship-pages-on-facebook/
* http://www.7xter.com/2015/02/how-i-hacked-your-facebook-photos.html
* http://roy-castillo.blogspot.com/2016/02/overwritingremoving-cover-photos-on.html
* https://blog.getwhitehats.com/a-simple-bug-on-facebook-that-is-worth-8000-6701787e1dbc
* http://arunsureshkumar.me/index.php/2016/09/16/facebook-page-takeover-zero-day-vulnerability/
* http://russellaurio.blogspot.com/2016/11/insecure-direct-object-reference-idor.html

### Privacy | Spam ($1500+)

* http://philippeharewood.com/ability-to-invite-any-user-to-a-facebook-page-all-non-friends/
* http://sweethacking.blogspot.com/2014/11/how-i-made-500-usd-by-reporting-logical.html
* http://patorjk.com/blog/2013/03/01/facebook-user-identification-bug/
* http://allanjaydumanhug.ninja/blog/facebook-privacy-bug-view-photos-as-a-blocked-user/
* https://abhartiya.wordpress.com/2014/12/23/a-bug-in-facebook-that-violated-my-privacy/
* http://josipfranjkovic.blogspot.com/2015/07/the-easiest-bug-bounties-i-have-ever-won.html
* http://www.pranavhivarekar.in/2016/02/20/facebooks-bug-fooling-graph-search-to-bypass-privacy-restrictions/
* https://abhartiya.wordpress.com/2016/02/08/ability-to-send-payment-requests-inspite-of-being-blocked-by-the-recipient/
* https://medium.com/@rajsek/curiosity-and-passion-to-your-profession-might-lead-to-make-your-dream-come-true-7d9be3c6029a
* https://medium.com/@rajsek/my-2nd-facebook-bounty-poc-fb-data-of-birth-disclosure-d02e1bec50
* https://dr4cun0.com/blog/silently-using-facebook-xmpp/
* http://philippeharewood.com/find-mingle-suggestions-for-any-facebook-user/
* http://philippeharewood.com/find-mingle-suggestions-for-any-facebook-user-revisited/
* https://medium.com/@armaanpathan/idor-was-leading-to-privilege-escalation-and-violating-the-facebook-policy-355c67c654e6

### Page Roles
* http://philippeharewood.com/tag-photos-as-a-page-analyst/
* http://philippeharewood.com/using-an-analyst-account-to-post-to-facebook-open-graph-objects/
* http://philippeharewood.com/like-any-facebook-page-as-a-page-analyst/
* http://philippeharewood.com/viewing-payment-information-as-an-ad-analyst/
* http://philippeharewood.com/view-the-job-applications-of-a-page-as-an-analyst/
* http://philippeharewood.com/deactivate-facebook-page-shop-as-an-analyst/
* http://philippeharewood.com/create-a-product-as-an-analyst-on-a-facebook-page-store/

### Facebook Ads
* https://pouyadarabi.blogspot.com/2015/03/facebook-bypass-ads-account-roles.html
* http://philippeharewood.com/ads-api-error-leads-to-ad-account-id-being-leaked-from-the-legacy-account-id/
* http://philippeharewood.com/view-the-ads-retention-curve-completion-rate-for-any-ad-account
* http://philippeharewood.com/de-anonymizing-facebook-ads/

### Facebook Groups
* http://thesecuritynews.com/project/how-i-was-able-to-post-in-any-facebook-group-on-behalf-of-its-members/
* https://www.facebook.com/notes/$2500-lakhpati-bug-at-facebook-gaining-access-to-files-of-a-closed-group/686615161373797
* https://medium.com/@rahulmfg/get-groups-doc-without-user-permission-facebook-graph-api-bug-5f19367373a2
* http://philippeharewood.com/the-group-idphotos-endpoint-isnt-obeying-the-publish_actions-and-user_groups-permission-requirement/
* http://zappstiko.blogspot.com/2017/02/facebook-group-hack-in-2015-i-reported.html

### Phone number
* https://medium.com/@neerajedwards/how-i-was-able-to-remove-your-instagram-phone-number-d346515e79c3
* http://philippeharewood.com/determine-a-user-from-a-private-phone-number/

### Email address
* http://stephensclafani.com/2013/07/09/obtaining-the-primary-email-address-of-any-facebook-user/
* http://www.dawgyg.com/2016/12/21/disclosing-the-primary-email-address-for-each-facebook-user/
* http://fogmarks.com/2016/04/03/facebook-invitees-email-addresss-disclosure/
* http://blog.internot.info/2014/05/facebook-skype-to-email-leak-3000-bounty.html
* http://philippeharewood.com/view-commerce-settings-and-email-for-any-page-shop/
* http://philippeharewood.com/view-the-assigned-roles-and-emails-of-an-instagram-account/

### IP address
* http://asad0x01.blogspot.com/2017/05/facebook-buggetting-other-users-ip.html

### Symlink Attack
* http://josipfranjkovic.blogspot.com/2014/12/reading-local-files-from-facebooks.html

###Accellion’s Secure File Transfer 
* http://blog.orange.tw/2016/04/bug-bounty-how-i-hacked-facebook-and-found-someones-backdoor-script.html


### XXE
* http://www.ubercomp.com/posts/2014-01-16_facebook_remote_code_execution
* http://attack-secure.com/hacked-facebook-word-document/


### LFI
* http://www.websecuritylog.com/2014/10/facebook--bug-bounty.html?spref=tw


### SQLi
* https://bitquark.co.uk/blog/2014/08/31/popping_a_shell_on_the_oculus_developer_portal
* http://josipfranjkovic.blogspot.com/2014/09/step-by-step-exploiting-sql-injection.html

### Jenkins
* http://blog.dewhurstsecurity.com/2014/12/09/how-i-hacked-facebook.html


### API
* http://asad0x01.blogspot.com/2017/05/facebook-bugcommentingon-non-friends.html
* http://stephensclafani.com/2014/07/08/hacking-facebooks-legacy-api-part-1-making-calls-on-behalf-of-any--user/
* http://roy-castillo.blogspot.com/2013/07/how-i-exposed-your-primary-facebook.html
* http://philippeharewood.com/facebook-insights-api-bug/
* http://philippeharewood.com/facebook-v2-0-api-bug-inconsistencies-with-app-scoped-ids/
* http://intothesymmetry.blogspot.in/2014/09/bounty-leftover-part-1.html
* http://philippeharewood.com/paging-cursors-leaking-data-in-graph-api/
* http://philippeharewood.com/tagged-places-shouldnt-show-paging-params-if-no-user_tagged_places-granted/
* http://philippeharewood.com/bypassing-appsecret_proof-verification/
* http://philippeharewood.com/change-the-description-of-a-video-without-publish_actions-permission/
* http://philippeharewood.com/icon-field-in-posts-gets-access_token-appended/
* http://philippeharewood.com/reply-to-a-message-without-read_page_mailboxes-permission/
* http://philippeharewood.com/bypassing-posting-to-friends-timelines-api-restriction/
* http://www.7xter.com/2015/03/how-i-exposed-your-private-photos.html
* http://philippeharewood.com/facebook-page-profile-picture-update-requires-neither-publish_pages-nor-publish_actions/
* http://philippeharewood.com/the-facebook-publish_pages-permission-is-missing-in-melinks/
* http://philippeharewood.com/upload-videos-thumbnails-with-just-public_profile-permission/
* http://philippeharewood.com/icon-field-in-posts-gets-access_token-appended/
* https://web.archive.org/web/20160202160841/* http://www.secinfinity.net/modifying-privacy-settings-on-facebook-through-graph-api/
* http://philippeharewood.com/show-friends-sharing-precise-locations-as-a-third-party-application/
* http://philippeharewood.com/change-tag-suggestions-for-any-facebook-user/
* http://philippeharewood.com/detailed-information-for-all-facebook-native-applications-as-a-non-employee/
* http://philippeharewood.com/send-a-location-ping-to-facebook-friends-using-only-public_profile-as-a-third-party-app/
* http://philippeharewood.com/third-party-developer-access-to-facebook-captcha-challenges/
* http://philippeharewood.com/vault-images-can-be-published-by-third-party-applications/
* http://philippeharewood.com/deleting-a-vault-image-makes-data-available-to-third-party-applications/
* http://philippeharewood.com/determine-the-number-of-friends-added-for-any-facebook-user/
* http://philippeharewood.com/determine-if-any-two-users-are-friends-without-user_friends-permission/
* http://philippeharewood.com/determine-if-any-two-users-are-friends-without-user_friends-permission-revisited/
* http://philippeharewood.com/creation-of-a-scrapbook-invalidates-the-privacy-set-for-a-non-user-family-member/
* http://philippeharewood.com/bypassing-posting-to-friends-timelines-api-restriction-revisited-in-photos/
* http://philippeharewood.com/add-a-user-to-the-list-of-facebook-contacts/
* http://thesecuritynews.com/project/accessing-the-number-of-active-users-of-any-application
* http://philippeharewood.com/view-instant-articles-traffic-lift-for-any-page/

### GraphQL
* http://philippeharewood.com/view-the-graphql-stored-queries-for-any-application/
* http://philippeharewood.com/path-disclosure-in-facebook-graphql-api/
* http://philippeharewood.com/facebook-employees-commission-splits-counts-are-shown/
* http://philippeharewood.com/abusing-facebook-graph-search/
* https://medium.com/@rajsek/my-3rd-facebook-bounty-hat-trick-chennai-tcs-er-name-listed-in-facebook-hall-of-fame-47f57f2a4f71
* https://pranavhivarekar.in/2017/02/11/facebooks-bug-unauthorized-access-to-credit-card-details-limited-of-any-user/


### FQL

* https://filippo.io/a-bug-worth-4200$/
* http://philippeharewood.com/facebook-keyword_insights-bug/
* http://philippeharewood.com/getting-the-username-in-fql-in-2-0-applications/

### Login Nonces
* https://stephensclafani.com/2017/03/21/stealing-messenger-com-login-nonces/


### OAuth (AKA Stealing Access Tokens)
* https://www.josipfranjkovic.com/blog/hacking-facebook-csrf-device-login-flow
* http://stephensclafani.com/2014/07/29/hacking-facebooks-legacy-api-part-2-stealing-user-sessions/
* http://isciurus.blogspot.ru/2013/04/a-story-of-9500-bug-in-facebook-oauth-20.html
* http://isciurus.blogspot.ca/2012/09/pwning-facebook-authorization-through.html
* http://homakov.blogspot.ca/2013/02/hacking-facebook-with-oauth2-and-chrome.html
* http://blog.bentkowski.info/2014/09/in-this-post-ill-explain-to-you.html
* https://prakharprasad.com/facebook-mailchimp-application-oauth-2-0-misconfiguration/
* http://medu554.blogspot.com/2013/08/facebooks-parse-oauth-bug.html
* http://www.nirgoldshlager.com/2013/03/how-i-hacked-any-facebook-accountagain.html
* http://www.nirgoldshlager.com/2013/02/how-i-hacked-facebook-oauth-to-get-full.html
* http://intothesymmetry.blogspot.in/2014/04/oauth-2-how-i-have-hacked-facebook.html
* http://blog.fin1te.net/post/47882639723/stealing-facebook-access-tokens-with-a-double
* http://prosecco.gforge.inria.fr/CVE/Facebook_JS_2012.html
* http://philippeharewood.com/swiping-facebook-official-access-tokens/
* http://whitehatstories.blogspot.in/2017/05/oauth-token-validation-bug-in-facebook.html


### Instagram
* http://www.iltalehti.fi/digi/2016050221506011_du.shtml
* https://viaforensics.com/mobile-security/hacked-your-instagram-account.html
* http://josipfranjkovic.blogspot.com/2013/07/how-i-found-my-way-into-instagrams.html
* http://www.breaksec.com/?p=6164
* http://insertco.in/2014/02/10/how-i-hacked-instagram/
* http://blog.fin1te.net/post/65636287908/instagrams-one-click-privacy-switch
* http://samanfatahpour.blogspot.com/2014/10/facebook-bugbounty-facebook-instagram.html
* https://www.arneswinnen.net/2016/02/the-tales-of-a-bug-bounty-hunter-10-interesting-vulnerabilities-in-instagram/
* https://www.arneswinnen.net/2016/03/how-i-could-compromise-4-locked-instagram-accounts/
* http://mohankallepalli.blogspot.com/2016/04/instagram-unauthorized-comment-deletion.html
* https://www.arneswinnen.net/2016/05/instabrute-two-ways-to-brute-force-instagram-account-credentials/
* http://bugdisclose.blogspot.in/2017/04/instagram-email-verification-issue.html
* http://philippeharewood.com/find-instagram-contacts-for-any-user-on-facebook/


### Signal
* http://philippeharewood.com/getting-facebook-signal-app-access-token/

### Slingshot

* http://philippeharewood.com/add-any-facebook-user-non-friend-to-slingshot-without-knowing-the-username/

### Moments
* http://philippeharewood.com/rewriting-a-photo-not-owned-by-the-session-user-in-moments-app/
* http://philippeharewood.com/delete-any-moments-app-photo-or-folder-not-owned-by-the-session-user/

### Moves
* http://www.paulosyibelo.com/2015/12/facebooks-moves-oauth-xss.html

### Whatsapp
* https://immukul.blogspot.in/2016/11/whatsapp-hacked.html
* http://blog.pentestnepal.tech/post/156707088037/i-got-emails-g-suite-vulnerability
* https://medium.com/@vishnu0002/whatsapp-dos-vulnerability-in-ios-android-d896f76d3253