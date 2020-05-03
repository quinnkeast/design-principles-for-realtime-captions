# Design Principles for Real-Time Captions in Video Calling

Over the last few months, workplace conversation and communication has adapted to the rise in remote work by shifting  largely to some form of video calling.

We're at a threshold where the technology exists to create a truly inclusive world for those living with hearing loss. Let's do it together - and get the details right.

For people living with hearing loss, video calls are broadly inaccessible and exclusive. But we're at a threshold where the technology exists to make these tools accessible to everyone. Google Meet now has real-time captions. Other real-time speech-to-text tools like Otter are flourishing.

The challenge: real-time captioning in video calls is a new problem space with its own risks, challenges, and opportunities. If we get it right, we'll create more accessible and inclusive platforms and workplaces. If we get it wrong, we can create frustration, stigma, and lasting social and professional damage. That's why we need clear and considered design principles to guide our efforts.

These are design principles I've identified that I believe any implementation of real-time captioning in video calling should adhere to. These principles together provide a positive, usable, and inclusive experience for participants who rely on captions for accessibility.

## Design Principles for Real-Time Captions in Video Calling Platforms

1. **Captions for video calling are their own medium with their own challenges.**  
The purpose and context that surrounds video calling is very different from watching television or movies. Treat captions for video calls as a unique challenge with its own context, constraints, and opportunities.

2. **Captions are content. Everything else is context.**  
A video call still works if someone's video is turned off because the audio is the content. Captions are the direct alternative to audio for those who rely on captions. This means captions should be prioritized over all else for people relying on captions. Captions should never be hidden or obscured.

3. **Protect the equality of all participants.**  
The act of using captions must not distinguish an individual from other conversational partners, such as by the direction of their gaze in relation to the screen and the subsequent perception of eye contact. Someone relying on captions should be indistinguishable from someone relying on audio.

4. **Don't single out the use of captions.**  
When joining a video call, all participants are aware that they are sharing their audio and video with other participants. Each participant can choose to share or not share their audio and video. People relying on captions should not be singled out as using captions, as captions aren't recordings: they're an alternate form of audio that other participants choose to share.

5. **Captions are a choice that must be present outside the immediate context of a video call.**  
Never put people in a position where they have gaps in accessibility. Give people control over enabling captions before they enter a conversation, in the same way people have control over their camera and microphone settings before they join a call. And respect their choices: if someone chooses to use captions, remember that choice for the next call.

6. **Prioritize something over nothing.**  
Humans are incredible at using context to derive meaning. Machine learning has a long way to go. That's why we should prioritize something over nothing. If the speech-to-text engine isn't confident in a specific transcription and is likely to make adjustments with further context, deliver it anyway with confidence indicators and make corrections as they become available.

7. **Protect the integrity of conversation.**  
Don't change what was spoken for the sake of brevity. Filler words like "um" and "uh" are a natural and functional part of conversations. Real-time captions for video calls aren't transcriptions and meet different needs.

8. **Provide extra context when possible.**  
People who rely on audio in video calls can identify who is talking, their emotional tone, and easily detect their own name among noise. Find ways to provide this context that people relying on captions may be missing.

9. **Provide constant and clear feedback about what's happening.**  
A real-time speech-to-text system is an inherent black box. That's why there needs to be constant feedback about what the system is doing: whether it's actively taking in audio, whether it's processing audio, and whether it's lagging or in real-time. Knowing that the system was aware something was said, but that it couldn't transcribe it, is useful information that can provide context that humans can use to derive useful meaning.

10. **Proactively provide feedback to all conversational partners when captions are slow or failing to work.**  
Don't make it the user's responsibility to interrupt and inform others when the captions aren't working. Provide feedback to all participants and allow everyone to contribute to creating an inclusive environment.

11. **Provide fallbacks for all users when captions experience a failure.**  
Text-based messaging places all participants on equal ground when captions experience failures such as network or processing errors. If a participant is relying on captions for accessibility, a failure should trigger a text-based messaging alternative for all users.

12. **Provide access to the complete conversation.**  
People who use audio in video calls can look away, dismiss a random notification, or close a window without losing track of the conversation. People relying on captions must have this same flexibility. Requiring constant and undivided visual attention to avoid missing content is unfair for people that rely on captions. In practice, this means giving people who use captions the ability to go back and see what they missed.

13. **Protect privacy in ongoing conversations.**  
When someone joins a video call already underway, they don't have access to what was already said unless the call was recorded. The same should apply for captioning. Only those who were part of the conversation should have access to that part of the conversation in the caption history.

14. **Prioritize offline processing, and clearly explain how privacy is protected during processing.**  
Give all participants information and assurance around how audio is processed and converted into text and what privacy implications exist as a result. Encryption and data concerns should apply equally to captions as to audio and video processing and streaming.

15. **Design captions for readability.**  
Treat captions as text content and design for readability using design heuristics. The beginning of each line should have a fixed location that lets users predictably direct their gaze, with sensible defaults for line length (about 45–75 characters) and line height (about 140%). Text should automatically scroll at the end of each line.

16. **Captions must be accessible in themselves.**  
Like any other text content, people must have control over the size, colour, and font choice used for captions. Some people may have difficulty reading smaller text, while others may rely on specific font choices. Use sensible defaults that meet accessibility guidelines, but provide individual control and choice.

17. **Captions must be movable and adjustable.**  
People relying on captions may need to relocate the caption element to meet specific individual needs that we may not be able to predict. Provide a sensible, well-designed default, but provide the ability to pop-out, move, and adjust the caption element according to individual needs.

These principles represent my own perspective on how to design inclusive real-time captioning for video calls. As we collectively explore this problem space, let's adjust and expand these principles in response to new insights and opportunities.
