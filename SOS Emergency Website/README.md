# SOS - Emergency Website

Support me by contributing with a [PayPal donation][donation].

## Description

With this workflow you can create an emergency website with minimal effort on your iPhone. You can share the site with as many or as little people you want. The goal is to have a modern distress signal at hand which gives your helpers a good overview of the situation at a glance.

[![SOS Emergency Website in One Step][cover]][youtube]

#### Demo Websites

**No 1:** http://sos.rocketink.net/donny.html

**No 2:** http://sos.rocketink.net/thedude.html

## Features

- Two modes
    - Me Mode: automatically pre-populates the contact section of the website with two of your emergency contacts ([ICE][]) and your family doctor – optionally you can select a third contact from the address book.
    - Third-Person Mode: allows you to select the person in distress from your address book. You can select up to three ICE contacts for this person, c.f. family members, the spouse or children. Additionally, since you're on site,  you will get added as a direct contact.
- Formats contact data from the iOS address book and generates a public vCard with…
    - a photo of you,
    - your phone number(s),
    - your address ( – in case you got more than one it grabs the first),
    - and additional information in the notes field.
- Allows you to add a brief description of what happened.
- With the help of your iPhones GPS sensor your current location will be displayed on the website as well as…
    - a button to open up a link that shows where you are in Google Maps (web browser version),
    - two buttons for opening the address in Google Maps or Apple Maps on the iPhone.
- After the website is online, you have the option to append additional images. You can select these from you photo library or take them with your iPhone camera.
- Support for localization so that you can build the website in your native language
    - Check the local folder in this repository to see if your language is supported. Feel free to submit translations for languages that aren't supported yet.

## Install

1. Install Workflow (http://workflow.is ☲ [affiliate link][]) from the Apps Store on your iPhone.
2. [Download][workflow] the Emergency Website workflow and open it in the app.
3. Mare sure you have it set up all the four variables at the top correctly. Each field that needs to be changed is marked with a setup instruction.
4. If you run Workflow for the first time, you will have to grant it access to your Dropbox (http://dropbox.com) – this is were the final site will get hosted on.
        ![Appendix](http://rocketink.net//uploads/2015/2015-06-12-workflow-comments.png)

Check out [**my article at RocketINK**][source] for additional tips on how use and customize the workflow.

## Troubleshooting

### Known Issues with Workflow

- The notes fields only won't update automatically. You have to remove and add the contact in case you update notes in the Contacts.app.
    - The same thing happens when you share this workflow via Air Drop.
- Workflow can't upload photos from the Photo Stream. Only images that are stored locally in your Camera Roll can be uploaded to Dropbox. However, it's unlikely that you want to add images from the Photo Stream in the case of an emergency.
- There is no fallback in case you are in a bad spot where there is no GPS signal. The workflow will abort when this happens.

## License

------

``` 
██████████████████████████████ 
Copyright 2015, Patrick Welker
          http://rocketink.net
██████████████████████████████ 
```

SOS – Emergency Website by Patrick Welker is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License][license]. SOS icon by Stefano Vetere  (Noun Project).

[source]: http://rocketink.net/2015/06/emergency-website.html
[license]: http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US
[donation]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=N8XY8C7ZDDULA
[affiliate link]: https://itunes.apple.com/us/app/workflow-powerful-automation/id915249334?mt=8&uo=4&at=10l8771&ct=github
[cover]: http://rocketink.net/uploads/2015/2015-06-12-youtube-cover.jpg
[youtube]: https://www.youtube.com/watch?v=OjrJ6FEBkwM&feature=youtu.be
[workflow]: https://github.com/pattulus/Workflows/raw/master/SOS%20Emergency%20Website/Emergency%20Website.wflow
[ICE]: https://en.wikipedia.org/wiki/In_case_of_emergency