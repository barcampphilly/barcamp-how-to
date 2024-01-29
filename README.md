# How to Run a BarCamp Philadelphia

BarCamp Philadelphia is an unconference by the Philly community, for the Philly community. The organization team morphs from year to year since its inception in 2008. It typically happens every Fall, although a few years were missed during the COVID-19 pandemic. This documentation serves as a "how-to" of what we've learned over the years. It is meant to be a living, breathing document as the event evolves.

If you're organizing this year: make it yours! BarCamp has always been an event where all ideas are valid, and consensus rules. It has always been organizer by unpaid volunteers.

## 1. Getting Space

BarCamp can't happen without space for the event. We have been lucky enough to hosting BarCamp at The Wharton School since 2012. Several Wharton staff can be contacted to help reserve the space for a date, including Tim Allen, Ryan Sullivan, Antonio Vivas, and JM Conway. Securing the space and a date must be completed before much else can be done.

## 2. Getting Organized: The Google Drive & Passwords to Accounts

* The Google Drive (https://drive.google.com/drive/u/0/folders/0BwpcySCEDd_8N05iM0pwWmg2Sjg) contains:
    * Separate sub-folders for each year of the event. Each year, we typically start by copying the previous year and pruning / modifying as necessary.
    * A "What is BarCamp" document (written for Wharton Operations)
    * A generic Sponsorship Prospectus which can be updated for each year with the date and exported to PDF
    * A folder for Graphical Assets, such as print-quality logos, t-shirts, badges, and Huntsman Hall floorplans 
    * The content playbook document
    * The Safe Spaces Policy
* Passpack: https://passpack.com/
    * We keep all of our passwords for BarCamp Philly accounts in Passpack.
    * The access credentials are kept in current organizers' password managers.

## 3. Getting Sponsors

* Make a copy of the generic Sponsorship Prospectus and update it for the current year. Save it in the current year's folder.
* Start with the previous years sponsorship spreadsheet, which should have contact information for all of the previous year's sponsors.

## 4. Tickets

[How to setup tickets at TicketLeap](README_tickets.md)

## 5. Accounts, Website Registrar and Hosting

* We have consolidated all important accounts under the `barcampphilly@gmail.com` email address. Account hosting used to be with MediaTemple, which was bought by GoDaddy. You can still query the old DNS records on MediaTemple with commands like `nslookup -q=mx barcampphilly.org ns1.mediatemple.net` or `nslookup -q=txt barcampphilly.org ns1.mediatemple.net`.
* The website is registered and hosted at NameCheap.com. Credentials are in PassPack.
    * After logging in, go to `Account -> Hosting List`
    * Domains are under `Domains`
    * DNS configuration is under `Zone Editor`
    * Add SSH keys for access to the server under `SSH Access -> Manage SSH Keys.` **RSA keys only! ed25519 is not supported.** See an example SSH config in PassPack.
    * 2013 - 2022 are flat HTML directories without version control. 2023 is a remote clone [of this repository](https://github.com/barcampphilly/bcp-14-2023), with a deployment key.

## 6. Communications and Promotion

* The BarCamp Philly [mailing list is on MailChimp](https://mailchimp.com/)
* [Instagram](https://www.instagram.com/barcampphilly/)
* [Facebook](https://www.facebook.com/barcampphilly/)
* [Twitter](https://twitter.com/barcampphilly)

## 7. Schwag

BarCamp Philly has needed several items printed in the past. These normally have a fairly long lead time - and we can get better prices the sooner we order:

* [T-Shirts](README_schwag.md#t-shirts)
* [Lanyards](README_schwag.md#lanyards)
* [Badges](README_schwag.md#badges)
* [Sponsor Banners](README_schwag.md#sponsor-banners)

## 8. Day of BarCamp Resources

A Django website with an Unconference app has been build and can be used year-after-year.

* [The Unconference App](https://github.com/flipperpa/unconference) (also [on PyPI](https://pypi.org/project/unconference/))
* [BarCamp Philly Django Scheduler](https://github.com/barcampphilly/django-scheduler) (Private Repo on GitHub)
    * Our instance is hosted at CodeRed Cloud. The URL is: https://barcampphillyschedule.codered.cloud/

## 9. Post-Conference To-Do List

* Send a thank you email to sponsors
* Call for volunteers for next year
* Send a final email to the email list
* Turn off the MailChimp subscription
* Update this documentation!
