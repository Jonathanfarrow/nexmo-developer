---
title: Conversation
description: A Conversation connects Users and allows them to communicate.
---

# Conversation

A Conversation is a shared core component that Nexmo APIs rely on. Conversations happen over multiple mediums (text, voice, video) and can have associated Users through Memberships.

The Conversation is key to understanding the Conversation API. In order for Users to communicate, they must connect to a Conversation, at which point they become Members of that Conversation. A Conversation is capable of supporting text messaging, audio calls, or video calls (which includes audio). For text messaging a Conversation can be thought of as like a chat room. Users can be invited to join a Conversation and they can leave a Conversation. A User can also join multiple Conversations.

The Container contains associated events. These events can be communication events such as messages, voice and video streams or other events such as added or removed users, typing indicators and so on.

There can be no communication outside of the context of a Conversation.

A Conversation can be used for a single temporary communication interaction with a beginning and end, such as a call. Alternatively, it can be utilized as a permanent container for the complete history of all related interactions.
