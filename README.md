# Deep-Face-Swap-Tool
This is a one-click face swap tool that allows you to take a video and replace the face in it with a face of your choice. You only need one image of the desired face. No dataset, no training required.

## Features

- **One-click face swap**: Easily swap faces in videos with a single image.
- **No dataset or training needed**: Just provide the source image and target video.
- **Multiple options for customization**: Various command-line arguments to fine-tune the face swap process.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/cizodevahm/Deep-Face-Swap-Tool.git
    cd roop
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Start the program with arguments:
```bash
python run.py [options]
```

## Example
```bash
python run.py -s source.jpg -t target.mp4 -o output.mp4
```

## Command-Line Options

```-h, --help```: Show help message and exit.

```-s SOURCE_PATH, --source SOURCE_PATH```: Select a source image.

```-t TARGET_PATH, --target TARGET_PATH```: Select a target image or video.

```-o OUTPUT_PATH, --output OUTPUT_PATH```: Select output file or directory.

```--frame-processor FRAME_PROCESSOR [FRAME_PROCESSOR ...]```: Frame processors (choices: face_swapper, face_enhancer, ...).

```--keep-fps```: Keep target fps.

```--keep-frames```: Keep temporary frames.

```--skip-audio```: Skip target audio.

```--many-faces```: Process every face.

```--reference-face-position REFERENCE_FACE_POSITION```: Position of the reference face.

```--reference-frame-number REFERENCE_FRAME_NUMBER```: Number of the reference frame.

```--similar-face-distance SIMILAR_FACE_DISTANCE```: Face distance used for recognition.

```--temp-frame-format {jpg,png}```: Image format used for frame extraction.

```--temp-frame-quality [0-100]```: Image quality used for frame extraction.

## Contributing

Contributions are welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](license) file for details.

