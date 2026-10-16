# AFTERHOURS — Real-Time YouTube Watch Party

## Project Overview

**AFTERHOURS** is a browser-based watch-party application that lets people watch YouTube videos together in a shared room. It brings synchronized viewing, a collaborative video queue, chat, reactions, polls, and host handover into one place.

**Live Demo:** Open the deployed demo link submitted alongside this project.
Demo link: [text](https://youtu.be/RiESu1LNosE?si=FB_S-HM5iBWJTiEM)

## Key Features

- **Create or join a room:** Create a watch room and invite others with its room code.
- **Shared playback:** The host controls playback and seeking; participants can use **SYNC ROOM** to resynchronize.
- **Collaborative queue:** Add YouTube video links, vote on what to watch next, sort the queue, and let the host load or remove videos.
- **Room chat:** Send messages that are shared with people in the room.
- **Live reactions:** Send animated emoji reactions during a watch session.
- **Polls:** Create polls, vote, view results, and close a poll.
- **Host handover:** Transfer host controls to another participant.
- **Responsive interface:** Designed for desktop and smaller screens.

## How to Evaluate

For the best demonstration, open the live demo in two separate browser profiles or on two devices so each participant has an independent session.

1. Create a room in the first session and join it from the second using the room code.
2. Add a video to the shared queue and vote from both sessions.
3. Test playback controls and **SYNC ROOM** with a video that allows embedding.
4. Send chat messages and emoji reactions from both sessions.
5. Create a poll, vote from each session, and check the results.
6. Transfer host controls and verify that the new host can control playback.

## Technology

- **Frontend:** HTML, CSS, and JavaScript
- **Room access and live data:** Firebase Authentication and Realtime Database
- **Video playback:** YouTube embedded player

## Project Files


.
├── index.html                   # Application interface, styling, and logic
├── firebase-database-rules.json # Database access rules
└── README.md                    # Project overview and evaluation guide

## Evaluation Notes

- Some YouTube videos cannot be played in an embedded player because of the video's settings or platform restrictions. Please choose a video that permits embedding when testing playback.
- Browser autoplay or audio policies may require a participant to interact with the page before playback starts.
- Playback synchronization can vary with network conditions and player behavior; the **SYNC ROOM** control is available to help participants resynchronize.
