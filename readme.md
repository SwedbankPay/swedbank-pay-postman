# Swedbank Pay Postman

This repository contains a Postman collection and environments for Swedbank Pay's API Platform.

## Quick start

- install [postman][download].
- open postman import window and add environments & collections under upload files. [Explanation if you're unsure][importFiles]
  - if you already have a setup in postman, you can also create a [new workspace][workspaces] to separate your own setup from this setup.
- Choose the environment you want to use and add your merchant ID and merchant token to that environment.
  - (Change semantic fluff like merchant name or description if you so desire)

## Usage

This postman collection is created for the purpose of creating payments using only the access that's publicly available.

## Creating new requests

If you want to create new requests and add to the collection, try to remember adding an example along with the request so whoever uses it can click example to see what is expected of input and output.

[Postman official documentation][documentation]

[SwedbankPay official documentation][SWBPayDocumentation]

[documentation]: <https://learning.postman.com/>
[download]: <https://www.postman.com/downloads/>
[importFiles]: <https://learning.postman.com/docs/postman/collections/importing-and-exporting-data/#importing-data-into-postman>
[SWBPayDocumentation]: <https://developer.swedbankpay.com/>
[workspaces]: <https://learning.postman.com/docs/postman/workspaces/creating-workspaces/>
