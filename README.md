# VODTracker

## Team Members
- [Brandon Rodriguez](bbranduhn)  
- [Xiaomin Liu](xl4624)  

## What and Why?  
VODTracker is a service designed to improve the way Twitch users replay or catch up on livestreams from their favorite creators. While Twitch does provide VODs (video-on-demand), the current design is limited:  
- Old VODs expire: Twitch automatically deletes VODs after a certain set period of time (Twitch Partners, Prime, and Twitch Turbo users have 60 days, and other broadcasters have 7 days source)  
- Delayed chat replays: Chat is not synchronized smoothly with VODs  
- No enhancements: the current system doesn’t provide navigation tools that help viewers catch up efficiently  
- Muted playback: Copyright detection mutes large sections of streams, even when the creator is speaking with background music  

## For whom?
The primary users are Twitch viewers, especially those who follow creators but can’t always watch live due to time zones or other commitments. These users revisit streams to watch gameplay segments, specific segments, or most viewed moments.  
Additionally, content creators who diversify their content and/or highlights across multiple social media platforms have access to a navigation tool that improves accessibility by automatically organizing VODs by activity. 
	
## How?
From the end-user perspective, VODTracker will offer:
- A permanent library of past streams that does not expire
- Searchable metadata so users can filter by date, stream title, categories, and tags
- Chapters within each VOD that automatically segment content based on category changes (e.g. switching games, “Just Chatting”, or sleeping)
- Improvements to the current Twitch UI by making it easier to find VODs, track view spikes, and synchronize chat replays with the video.

## Scope
This project is reasonable for a team of 4-6 developers to build over a semester, with the deliverables being:
- A backend that can record VODs from Twitch with a database that can store VOD metadata.
- A frontend that for browsing VODs and playing past streams
- We want to target just one small streamer to keep the scope manageable.
