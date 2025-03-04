===============
 License Types
===============

.. contents:: Contents
   :depth: 2
   :local:
   :backlinks: top

.. highlight:: console

Introduction
============

This documentation is only apply to Pyarmor_ 8.0 plus.

Pyarmor is published as shareware, free trial version never expires, but there are some limitations:

(1) Can not obfuscate big scripts [1]_
(2) Can not use feature mix-str [2]_ to obfuscate string constant in scripts
(3) Can not use RFT Mode [3]_, BCC Mode [4]_
(4) Can not be used for any commercial product without permission
(5) Can not change runtime package name "pyarmor_runtime_000000"
(6) Can not be used to provide obfuscation service in any form
(7) Can not use obf-code > 1

These limitations can be unlocked by different License Types except last one.

License types
=============

Pyarmor has 3 kind of licenses:

.. glossary::

    Pyarmor Basic

        Basic license could unlock limitations (1) (2) (4) (5) (7).

        Each obfuscation need online verify license.

    Pyarmor Pro

        Pro license could unlock limitations (1) (2) (3) (4) (5) (7).

        Each obfuscation need online verify license.

    Pyarmor Group

        Group license could unlock limitations (1) (2) (3) (4) (5) (7).

        Group license supports unlimited dockers which uses default bridge network and not highly customized. For Pyarmor Basic or Pyarmor Pro, up to 100 runs in 24 hours.

        Offline obfuscation, it need not internet connection when obfuscating the scripts.

Refer to :doc:`use Pyarmor License <how-to/register>`

For the obfuscated scripts run in the customer's device, Pyarmor has no any limitations, it's totally controlled by users. Pyarmor only cares about build machine.

Each license has an unique number, the format is ``pyarmor-vax-xxxxxx``, which x stands for a digital.

Each product requires one License No. So any product in global also has an unique number in Pyarmor world.

If user has many products, and has purchased one license for the first product. The second product could use first product license only if sale income of the second product less than 30x license fees. Once greater than 30x license fees, the second product need purchase its own license. It's same to user's other products.

One product in Pyarmor world means a product name and everything that makes up this name.

It includes all the devices to develop, build, debug, test product.

It also includes product current version, history versions and all the future versions.

One product may has several variants, each variant name is composed of product name plus feature name. As long as the proportion of the variable part is far less than that of the common part, they're considered as "one product".

Pyarmor License could be installed in many machines and devices which belong to licensed product. But there is limitation to be used at the same time.

In 24 hours only less than 100 devices can use one same Pyarmor License. Pyarmor License be used means use any feature of Pyarmor in one machine. Running obfuscated scripts generated by Pyarmor is not considered as Pyarmor License be used.

In details read `EULA of Pyarmor`_

**What's one product**

First of all, if not for sale, all the Python scripts are belong to one product "non-profits".

Pyarmor is one product, it includes:

* Pyarmor basic, Pyarmor pro, and Pyarmor group
* pyarmor-webui which provides graphics interface for pyarmor.
* the order system of Pyarmor is a Django's app running in cloud-server. This Django's app also belongs to one product Pyarmor.
* the laptop used to develop Pyarmor, the PCs used to test Pyarmor, the cloud-server to serve order system of Pyarmor, all of them belong to one product Pyarmor.
* Pyarmor 7.x, Pyarmor 8.x and Pyarmor 9.x

Microsoft Office is not one product, because each product in Microsoft Office is functional independence. For example, Microsoft Word and Microsoft Excel belong to Microsoft Office, but they're totally different.

Microsoft Word is one product, and Microsoft Word 2003，Word 2007 etc. are belong to one product Microsoft word.

License features
----------------

.. table:: Table-1. License Features
   :widths: auto

   ===================  ========   ========   =========   ========  ==============
   Features             Trial      Basic      Pro         Group     Remark
   ===================  ========   ========   =========   ========  ==============
   Basic Obfuscation       Y          Y          Y           Y       [5]_
   Expired Script          Y          Y          Y           Y       [6]_
   Bind Device             Y          Y          Y           Y       [7]_
   JIT Protection          Y          Y          Y           Y       [8]_
   Assert Protection       Y          Y          Y           Y       [9]_
   Themedia Protection     Y          Y          Y           Y       [10]_
   Big Script              No         Y          Y           Y
   Mix Str                 No         Y          Y           Y
   obf-code > 1            No         Y          Y           Y       [11]_
   RFT MODE                No         No         Y           Y
   BCC MODE                No         No         Y           Y
   Unlimited dockers       Y          No         No          Y       [12]_
   ===================  ========   ========   =========   ========  ==============

.. rubric:: notes

.. [1] Big Script means file size exceeds a certain value.
.. [2] Mix Str: obfuscating string constant in script
.. [3] RFT Mode: renaming function/class/method/variable in Python scripts
.. [4] BCC Mode: Transforming some Python functions in scripts to c functions, compile them to machine instructions directly
.. [5] Basic Obfuscation: obfuscating the scripts by default options
.. [6] Expired Script: obfuscated scripts has expired date
.. [7] Bind Device: obfuscated scripts only run in specified devices
.. [8] JIT Protection: processing some sensitive data by runtime generated binary code
.. [9] Assert Protection: preventing others from hacking obfuscated scripts
.. [10] Themedia Protection: using Themedia to protect Windows dlls
.. [11] ``--obf-code=2`` is new in Pyarmor 8.2
.. [12] This feature is introduced in Pyarmor 8.3, group license supports unlimited dockers, basic and pro licenses only allow 100 runs one day.

Purchasing license
==================

Open shopping cart in any web browser:

    https://order.mycommerce.com/product?vendorid=200089125&productid=301044051

If you have Pyarmor 8.0+ installed, this command also could open shopping cart::

    $ pyarmor reg --buy

In the shopping cart, select License Type and complete the payment online.

Please fill reg-name with personal or company name when placing order.

.. list-table:: Table-2. License Prices
   :header-rows: 1

   * - License Type
     - Net Price($)
     - Remark
   * - Basic
     - 52
     -
   * - Pro
     - 89
     -
   * - Group
     - 158
     -

An activation file named ``pyarmor-regcode-xxxx.txt`` will be sent by email immediately after payment is completed successfully.

Following the guide in activation file to take the purchased license effects. Or check :doc:`../how-to/register`

There are no additional license fees, apart from the cost of the license. And it only needs to be paid once, not periodically

Refund policy
-------------

If activation file isn't used, and purchasing date is in 30 days, refund is acceptable. Please

1. Email to Ordersupport@mycommerce.com with order information and ask for refund.
2. Or click `FindMyOrder page`_ to submit refund request

Out of 30 days, or activation file has been used, refund request will be rejected.

.. _FindMyOrder page: https://www.findmyorder.com/store?Action=DisplayEmailCustomerServicePage&Env=BASE&Locale=en_US&SiteID=findmyor


.. _upgrading old license:

Upgrading old license
=====================

Not all the old license could be upgraded to latest version.

The old license could be upgraded to Pyarmor Basic freely only if it matches these conditions:

* Following new `EULA of Pyarmor`_
* The license no. starts with ``pyarmor-vax-``
* The original activation file ``pyarmor-regcode-xxxx.txt`` exists and isn't used more than 100 times
* The old license is purchased before June 1, 2023. In principle, the old license purchased after Pyarmor 8 is available could not be upgraded to new license.

If failed to upgrade the old license, please purchase new license to use Pyarmor latest version.

The old license can't be upgraded to Pyarmor Pro and Group.

..
  But there is discount for old users to purchase Pyarmor Pro.

  .. list-table:: Table-3. Pyarmor Pro Discount for Old Users
     :header-rows: 1

     * - Old License Purchased Date
       - Discount(%)
       - Remark
     * - Between 2022-06-01 and 2023-05-31
       - 40
       -
     * - Between 2021-06-01 and 2022-05-31
       - 30
       -
     * - Before 2021-05-31
       - 20
       -

  Please send your order no. to pyarmor@163.com to request discount coupon, this request must be sent from registration email.

Upgrading old license to Pyarmor Basic
--------------------------------------

First find the activation file ``pyarmor-regcode-xxxx.txt``, which is sent to registration email when purchasing the license.

Next install Pyarmor 8.2+, according to new `EULA of Pyarmor`_, each license is only for one product.

Assume this license will be used to obfuscate product ``XXX``, run this command::

    $ pyarmor reg -u -p "XXX" pyarmor-regcode-xxxx.txt

Check the upgraded license information::

    $ pyarmor -v

After upgrade successfully, do not use activation file ``pyarmor-regcode-xxxx.txt`` again, it's invalid now. A new :term:`registration file` like :file:`pyarmor-regfile-xxxx.zip` will be generated at the same time.

In other devices using this new :term:`registration file` to register Pyarmor by this command::

    $ pyarmor reg pyarmor-regfile-xxxx.zip

After successful registration, all obfuscations will automatically apply this license, and each obfuscation requires online license verification.

If old license is used by many products (mainly old personal license), only one product could be used after upgrading. For the others, it need purchase new license.

..
  Upgrading old license to Pyarmor Pro
  ------------------------------------

  Upgrading old license to Pyarmor Pro needs extra fees.

  .. list-table:: Table-3. Upgrade fee from old license
     :header-rows: 1

     * - License Type
       - Upgrading fee($)
       - Remark
     * - Basic
       - 0
       - following new EULA and match some conditions
     * - Pro
       - 50
       -
     * - Group
       - N/A
       -

  Open shopping cart in any web browser:

      https://order.mycommerce.com/product?vendorid=200089125&productid=301044051

  If you have Pyarmor 8.2+ installed, this command also could open shopping cart::

      $ pyarmor reg --buy

  In the shopping cart, select ``Pyarmor-upgrade`` and complete the payment online.

  A file named ``pyarmor-regcode-to-pro.txt`` will be sent by email immediately after payment is completed successfully.

  This file includes the guide  to upgrade old license to Pyarmor Pro.

  Internet connection and Pyarmor 8.2+ are required to upgrade old license, check Pyarmor version by this command

      pyarmor -v

  Check old license

      pyarmor-7 -v

  If no old license found, register old license first

      pyarmor-7 register pyarmor-regcode-xxxx.txt

  Assume this license will be used to obfuscate product ``XXX``, run this command::

      $ pyarmor reg -u -p "XXX" pyarmor-regcode-xxxx.txt

  Check the upgraded license information::

      $ pyarmor -v

  After upgrade successfully, the file ``pyarmor-regcode-to-pro.txt`` is invalid. A new :term:`registration file` like :file:`pyarmor-regfile-xxxx.zip` will be generated at the same time.

  In other devices using this new :term:`registration file` to register Pyarmor by this command::

      $ pyarmor reg pyarmor-regfile-xxxx.zip

  After successful registration, all obfuscations will automatically apply this license, and each obfuscation requires online license verification.

  If old license is used by many products (mainly old personal license), only one product could be used after upgrading. For the others, it need purchase new license.

.. include:: _common_definitions.txt
