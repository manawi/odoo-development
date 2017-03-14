============
 Amazon EC2
============

Why we use EC2?
===============

To test payment_paypal module with a developer paypal account

How to get EC2 server?
======================

* Make amazon account
* Go to https://aws.amazon.com/ and create new personal account.
.. image:: /images/amazon-aws/amazon_ec2_account.png
.. image:: /images/amazon-aws/amazon_ec2_account_register.png
* Verify your credit card information is correct. Also, check your credit card activity to see if there’s a $1 authorization (this is not a charge).
* Check your email to see if you have received any requests to sign up confirmation
* Your services may take up to 24 hours to fully activate.
* Sign in to the console
* Go to ``Services >> Compute >> EC2``
* Click button ``[Launch Instance]``
* Select "Ubuntu 14.04"
* Choose an Instance Type "t2.micro" and click button ``[Review and Launch]``
* Click button ``[Launch]``
* Click button ``[Download Key Pair]``
.. image:: /images/amazon-aws/amazon1.png
* Save dowloaded file ``my_ec2.pem`` in your home dir and click button ``[Launch Instances]`` 
* From ``Instances >> Instances`` you can see current state of your server 
.. image:: /images/amazon-aws/amazon2.png
* Click button ``[Connect]``, select "A standalone SSH client" and follow the instructions
.. image:: /images/amazon-aws/amazon3.png
* Install odoo in your instance :doc:`Install odoo <../admin/install>` 
