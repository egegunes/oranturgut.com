+++
fragment = "contact"
disabled = true
date = "2017-09-10"
weight = 1100
#background = "light"
form_name = "defaultContact"

title = "Bize Ulaşın"
subtitle  = ""

# PostURL can be used with backends such as mailout from caddy
post_url = "https://example.com/mailout" #default: formspree.io
email = "mail@example.com"
button = "Gönder" # defaults to theme default
#netlify = false

# Optional google captcha
#[recaptcha]
#  sitekey = ""

[message]
  #success = "" # defaults to theme default
  #error = "" # defaults to theme default

# Only defined fields are shown in contact form
[fields.name]
  text = "Adınız *"
  #error = "" # defaults to theme default

[fields.email]
  text = "E-posta adresiniz *"
  #error = "" # defaults to theme default

[fields.phone]
  text = "Telefonunuz *"
  #error = "" # defaults to theme default

[fields.message]
  text = "Mesajınız *"
  #error = "" # defaults to theme default

# Optional hidden form fields
# Fields "page" and "site" will be autofilled
[[fields.hidden]]
  name = "page"

[[fields.hidden]]
  name = "someID"
  value = "example.com"
+++
