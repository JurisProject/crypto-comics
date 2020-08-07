---
id: doc6
title: Build Your Own CAO
sidebar_label: Build Your Own CAO
---

## Overview

This page will walk you through how to deploy your own Cooperative Autonomous Organization.

## Prerequisites

- An Ethereum wallet.
- At least 0.1 `ETH` (likely 0.3 or more).
- At least 25 `DAI` (likely more).
- A few hours of time.
- A name and mission statement for your CAO.

## DAO

First go to the [Aragon DAO creation page](https://mainnet.aragon.org/#/create) and select the Membership template.

Choose your DAO's name as well as voting parameters. For voting we recommend 10% quorum (how many people have to show up to vote) and a 60% approval threshold (of the people who show up, how many have to vote yes for a proposal to pass). Then deploy your DAO (at the time of writing this costs between 0.1 and 0.3 `ETH` depending on the gas fees).

## Cooperative

The first step is to create the [articles of incorporation](https://github.com/burrrata/crypto-comix/blob/master/juris/output.md) for your cooperative. Open [this file](https://github.com/burrrata/crypto-comix/blob/master/juris/output.md) and copy the text into a text editor that can export PDF documents. Then search and replace everything in {{ }} with things specific to your cooperative:

- {{NAME}} => The name of your organization.
- {{PURPOSE}} => The mission statement of your organization.
- {{TOKEN}} => The membership token of your DAO.
- {{DAO-ADDRESS}} => The Ethereum address of your DAO (not the ENS name, but the organization address).

Once you've searched and replaced, then export the document as a PDF.

The next step is to register your cooperative in the state of Wyoming. To do this you will need to print your PDF. You'll also need to print out [this form](https://sos.wyo.gov/Forms/Business/NP/NP-ArticlesIncorporation.pdf) and fill it out. Then mail both to `TBD` along with a $25 check.

## Getting help

If you need help deploying your DAO, filling out your articles of incorporation, or registering your entity you can reach out to `TBD` to set up a consultation. They'll be able to anser your questions and help you get started.