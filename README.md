Final Application Proposal for MSSE 661 Web Software Development

Abstract
========

My project will be an online savings application that supports 1-to-many
saving goals. The user will be able to login securely. The user can
setup 1-to-many goals with a name of their choosing like "Christmas
Gifts', "Vacation", "Bike", etc. Each goal will have a saved transaction
history. Progress will be presented visually. There will also be a
calculator to help determine goal amount or target date based on a
starting balance and incremental contributions.

High Level Design
==============

This application will have start page to create an account or to
sign-in. There will be an authentication component to facilitate unique
and secure accounts. The front-end will allow creation, update and
delete of defined user savings goals. It will also visually show
progress similar to a dashboard. The back-end will store user goal
information. A database will be used to store and query user data.

MVP - Mimimum Viable Product
===============

The core features I will focus on are
1. Register/login
2. Create a savings goal with initial amount and time that will calculate term to meet the goal
   1. Attention will given to calculations of monies suggested in previous peer review
3. Ability to retrieve the goal and modify progress

Stretch Objectives
===============

1. Visually show progress towards goal
2. Ability to create/modify/delete multiple goals

Basic Technologies
===============

As this is a totally new world for me, this application will build upon the framework from the
weeky class application. The backend database will be MySQL for Windows, with 2 tables - users (authentication)
and goals. TBD is how to tie the users to the goals. Initial thoughts are to capture the userID and store it
in the goals table. As this is new for me - some thought and research may be needed here. At this time I do not
see a need for more than 2 tables.

Intallation
===============

TBD


