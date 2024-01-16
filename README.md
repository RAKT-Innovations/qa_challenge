# QA Analyst Challenge - QuickSync

## Overview

This project is a SAAS application that allows users to keep their Online Store in sync with Online Stores from other platforms they own:

*   Users can sign up for a free trial for 15 days, using one of several possible market-places/online-store integrations we have;
*   Our app will then monitor the store for any activity, such as product updates and inventory quantity changes;
*   When a second store is connected, the user can benefit of automatically syncing those stores.

## Requirements

To test on this project, you will need the following:

> When creating your shopify development store, check the box for automatically creating products, so you have products to perform your tests.

*   Use Shopify's documentation from [this link](https://help.shopify.com/en/partners/dashboard/managing-stores/development-stores#create-a-development-store-for-testing-apps-or-themes), to sign up for a shopify partner account, and get yourself a development store. (It's as easy as signing up)
*   Create your development store with the name `qa-challenge-<yourfirstname>-<yourlastname>`
*   A second store. You can use the same shopify partner account you just created and follow the instructions from the link above. (Store name could be `qa-challenge-<yourfirstname>-<yourlastname>-2`)

## Usage

*   Go to [https://quicksync.pro](https://quicksync.pro) and `sign up` using your shopify `store name`;
*   Follow through the installation steps on-screen;
*   Wait for your products to be fetched;
*   Follow the instructions provided via the notification system on your dashboard;
    *   Connect second store;
    *   Connect locations if needed;
    *   Sync your products;

## Extra Information

Within our App, `Locations` can be more easily interpreted as warehouses where you have your products' inventory. If your products are stored in multiple locations, you may need to `Connect` a location on store `A` a location on store `B` to be synced. If the app detects multiple location you should see a Button for that, right after all the products are fetched.

## Challenge

> Please submit everything in PDFs

Explore the application to its full extent, by experimenting with all the the possibilities you can find.

It's expected that you:

*   Understand the entire product and document all the ways it can be used, and how;
*   Create all types of test cases you can, to showcase your expertise (Performance, UI, Compatibility, Reliability, Regression...);
*   For each task, document the steps you followed to complete, the expected and actual outcomes of the task, and provide as much information as you normally would on how to reproduce;
*   Provide one feature suggestion, along with its full Task/User-Story, with acceptance criteria;
*   Report at least one bug you can find, with as much information as you normally would, as if the developers could just take it and work on a fix;
*   Give us a list of tasks you would like perform if you had more time;
*   `As a Bonus:` If you have experience with `PlayWright`, we'd enjoy seeing some form of automated tests with structure for further improvement and overall continuous implementation.

  

It's expected that you finish this challenge within 4 days after you've received.

  

Thank you for participating in this challenge and good luck! 🍀
