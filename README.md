
# Payment Provider Logos

Official and [Image Service] available payment provider logos.

  - [Usage](#usage)
  - [Adding or modifying logos](#adding-or-modifying-logos)
  - [Contact](#contact)
  - [Licence](#licence)


## Usage

As with all image sets, these logos are available via the [Image Service].

To get a logo from the Image Service, use the following URL (replace the `product_source` with your product name and `logo_name` with the name of the logo you want)

```
https://www.ft.com/__origami/service/image/v2/images/raw/ftpayment:{logo_name}?source={product_source}
```

So to get the Visa logo:

```
https://www.ft.com/__origami/service/image/v2/images/raw/ftpayment:visa?source=test
```

The Image Service will convert these images on the fly if you pass in the right parameters. To find out more about this, please see the [Image Service documentation]


## Adding or modifying logos

Payment provider logos must only be added or modified with the approval of the Origami team and the legal department. Please open an issue on this repo or [Contact Origami](#contact) to discuss any changes that you need.

To keep logos consistent, please follow these guidelines:

  - Logos must be SVG format
  - Logo names must be lower case with words hyphenated:
    - **good**: visa.svg, direct-debit.svg
    - **bad**: VISA.svg, direct_debit.svg
  - Logos must be added to the `src` directory

**Please do not delete logos without talking to the Origami team who will need to manage the deprecation process**


## Contact

If you have any questions or comments about this image set, or need help using it, please either [raise an issue][issues], [visit #ft-origami on Slack][slack] or [email Origami Support][email].


## Licence

This software is published by the Financial Times under the [MIT licence].

TODO add the licenses for individual provider logos.



[email]: mailto:origami-support@ft.com
[image service]: https://www.ft.com/__origami/service/image/v2
[image service documentation]: https://www.ft.com/__origami/service/image/v2/docs/api
[issues]: https://github.com/Financial-Times/origami-payment-images/issues
[mit licence]: http://opensource.org/licenses/MIT
[slack]: https://financialtimes.slack.com/messages/ft-origami/
