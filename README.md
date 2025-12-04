Overview

EventLotteryApp is an Android application built with Java and Firebase Firestore, designed to make registration for high-demand community events fair, efficient, and accessible.

Instead of forcing users to race to register the moment an event opens, this app allows entrants to join a waiting list during an open registration window. When the window closes, a lottery system randomly selects participants, notifies them, and manages replacements if someone declines.

This ensures equal opportunity for people with work, accessibility, or schedule limitations.

Features
👤 Entrant Features

Browse events open for registration

Join or leave event waiting lists

Scan QR codes to quickly access event details

Receive lottery notifications (selected / not selected)

Accept or decline invitations

View profile & update personal details

See history of past registrations

Device-based identification (no required login)

🧑‍💼 Organizer Features

Create and publish events with posters, dates, and registration windows

Generate QR codes for event promotion

View and manage entrant waiting lists

Enable/disable geolocation requirements

Trigger lottery sampling for selection

Send targeted notifications (selected, waiting list, cancelled)

Draw replacement entrants if someone cancels

Export final list of confirmed attendees as CSV

Manage cancelled, selected, and enrolled lists

🛡️ Admin Features

Remove events, images, and profiles

Browse and review all system-level content

Monitor notifications sent by organizers

Remove organizers who violate policy

🔥 System Architecture Highlights

Clean, modular Java + XML codebase

Firebase Firestore for scalable, realtime data

QR code scanning with ZXing / ML Kit

RecyclerView-based UI for efficient lists

MVVM / MVC-inspired structure

Offline support for certain screens

Git version control & documented workflows
