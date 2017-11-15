============
This is text
============

This guide is a test different APIs provided by AWS, including the `S3`_ and `S3API`_ ones.

test subritile
==============

The configuration of the client depends on whenether you use a `TempAuth`_ or `Keystone`_ authentication on the Swift proxy.

one more
--------

To use the AWS command, you need to set your credentials in the `~/.aws/credentials` file:

   .. code-block:: console

      # mkdir ~/.aws
      # echo "[default]
      aws_access_key_id=demo:demo
      aws_secret_access_key=DEMO_PASS" >~/.aws/credentials
