# BLOCK REFERRER SPAM
SetEnvIfNoCase Referer 4webmasters.org spammer=yes
SetEnvIfNoCase Referer 7makemoneyonline.com spammer=yes
SetEnvIfNoCase Referer best-seo-offer.com spammer=yes
SetEnvIfNoCase Referer best-seo-solution.com spammer=yes
SetEnvIfNoCase Referer buttons-for-website.com spammer=yes
SetEnvIfNoCase Referer buy-cheap-online.info spammer=yes
SetEnvIfNoCase Referer free-share-buttons.com spammer=yes
SetEnvIfNoCase Referer get-free-traffic-now.com spammer=yes
SetEnvIfNoCase Referer semalt.com spammer=yes
SetEnvIfNoCase Referer seoanalyses.com spammer=yes
SetEnvIfNoCase Referer st3.cwl.yahoo.com spammer=yes
Order allow,deny
Allow from all
Deny from env=spammer
