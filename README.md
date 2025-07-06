# ComfyUI_SoundFlow 🎶

Welcome to **ComfyUI_SoundFlow**, a collection of nodes designed to enhance your sound work in ComfyUI. This repository aims to provide tools that simplify audio processing tasks, making your workflow smoother and more efficient.

## Available Nodes

This repository includes the following nodes:

- **Mixer**: Blend multiple audio sources seamlessly.
- **Silence Trimmer**: Remove silent sections from your audio files.
- **Concatenator**: Join multiple audio clips into one.
- **Get/Set Length**: Easily manage the length of your audio tracks.
- **Trim**: Cut audio to your desired length.
- **Fade In/Out**: Add smooth transitions to your audio.
- **Ducking**: Automatically lower the volume of background audio when a primary audio source plays.
- **Simple Compressor**: Control the dynamic range of your audio for a balanced sound.
- **7-Band Equalizer**: Fine-tune your audio across seven frequency bands.
- **Preview/Player**: Play back your audio to check changes in real-time.

The nodes marked with an asterisk (*) require additional functionality provided by the compiled Rust library (effects.dll). Currently, this library is available only for Windows, but I plan to support Linux and Mac in the future.

![ComfyUI SoundFlow](https://github.com/user-attachments/assets/3be18f5c-bf50-48ee-bc27-9cbedb27a579)

## Installation

To get started, clone this repository into your ComfyUI custom nodes directory:

```bash
git clone https://github.com/fredconex/ComfyUI_SoundFlow.git
```

After cloning, ensure that you follow any additional setup instructions provided in the repository.

## Usage

Once you have installed the nodes, you can access them within ComfyUI. Each node has specific functionalities that can be combined to create complex audio workflows. 

1. **Mixer**: Drag and drop your audio files into the mixer node. Adjust the levels to achieve the desired blend.
2. **Silence Trimmer**: Connect your audio to the silence trimmer node. It will automatically remove silent parts.
3. **Concatenator**: Feed multiple audio clips into the concatenator node. The output will be a single continuous audio file.
4. **Get/Set Length**: Use this node to specify the exact length of your audio track.
5. **Trim**: Connect your audio and set the start and end points to trim unwanted sections.
6. **Fade In/Out**: Add this node at the beginning or end of your audio to create a smooth fade effect.
7. **Ducking**: Set the parameters for the ducking node to ensure your main audio stands out.
8. **Simple Compressor**: Adjust the threshold and ratio to control the dynamics of your audio.
9. **7-Band Equalizer**: Use this node to adjust frequencies according to your preferences.
10. **Preview/Player**: Test your audio workflow before finalizing.

## Additional Features

### Compatibility

The nodes are designed to work with ComfyUI, a user-friendly interface for audio processing. The functionality of certain nodes may vary based on your operating system due to the Rust library dependency.

### Contributions

I welcome contributions to this project. If you have ideas for new nodes or improvements, feel free to submit a pull request. Your input can help make this tool even better.

### Issues

If you encounter any issues while using the nodes, please report them in the "Issues" section of this repository. I aim to address any problems promptly.

## Credits

This project is created by Alfredo Fernandes. If you find value in this tool and wish to support its development, consider making a donation.

[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/donate/?hosted_button_id=24CJHH95X3AQS)

## Releases

For the latest updates and versions, please visit the [Releases](https://github.com/Gaurav290303/ComfyUI_SoundFlow/releases) section. Here, you can download and execute the latest files.

## Future Plans

I plan to enhance this repository with additional nodes and features based on user feedback. My goal is to create a comprehensive toolkit for sound work that meets the needs of various users.

### Feedback

Your feedback is essential. If you have suggestions or comments, please feel free to reach out. Constructive criticism helps improve the project.

## Getting Help

If you need assistance, check the documentation included in the repository. You can also find helpful resources online regarding ComfyUI and audio processing.

## Community

Join the community of users who are working with ComfyUI and share your experiences. Collaborating with others can lead to new ideas and solutions.

## Conclusion

Thank you for exploring **ComfyUI_SoundFlow**. I hope these nodes enhance your audio projects and make your workflow more efficient. Happy sound designing!