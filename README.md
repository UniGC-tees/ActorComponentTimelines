# Why would you use this over a regular timeline?
- usable within actor components
- doesnt require ticking each frame
- keyframes editable at runtime
# Keyframes
<img width="388" height="483" alt="image" src="https://github.com/user-attachments/assets/f4a708e4-2e85-4772-908c-4fd31768329a" />

Linearly interpolate between as many values as you need within a set timeframe at specific points in time through the use of an array of keyframes, rather than Unreal's graph you may be used to.

Since my version of timelines take a regular array stored in memory over curves stored as an asset, it is possible to edit keyframes at runtime which is actually not possible even in Unreal's own timelines!!

<img width="1280" height="310" alt="image" src="https://github.com/user-attachments/assets/18ae1064-7c8e-4ad0-b5ec-a939f7f8d371" />

# Full functionality
<img width="352" height="437" alt="image" src="https://github.com/user-attachments/assets/f812c663-6df5-4f71-bfa0-3376c05e40eb" />

Fully functional start to end timeline with the ability to play, stop, and reverse from any new set time.

My timelines come with the added feature that you can specify how often they should update, which can be usful for things that dont need to update every.

Once again the offical one can't even do this, being forced to tick every frame.
<img width="1280" height="273" alt="image" src="https://github.com/user-attachments/assets/c9c199fc-9fa8-4c36-8196-47c9843e4af0" />

# Encapsulation
<img width="337" height="189" alt="image" src="https://github.com/user-attachments/assets/a515a813-8a18-48d4-9169-7895ae115e1e" />

Each layer of usability is encapsulated within the next, meaning for situations that don't require keyframes or even don't require the tracking of time at all don't have to incude them.
