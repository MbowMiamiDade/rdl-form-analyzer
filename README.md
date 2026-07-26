# Dumbbell Romanian Deadlift Form Analyzer

This project uses Python and Google MediaPipe Pose to analyze still images of the two-handed dumbbell Romanian deadlift. The program detects body landmarks and calculates three measurements at the bottom position of the movement:

- Hip angle
- Knee angle
- Torso lean

The measurements are compared with predetermined angle ranges to identify whether the position is within the expected range. The program also creates annotated images and a batch summary table.

## Technologies Used

- Python
- Google MediaPipe Pose
- OpenCV
- NumPy
- Matplotlib
- Pandas
- Google Colab

## Angle Ranges

- Hip angle: 60°–130°
- Knee angle: at least 130°
- Torso lean: 25°–75° from vertical

## Limitations

This project is a proof of concept. It uses a small dataset of still images and only analyzes the bottom position of the movement. Results depend on clear side-view images and accurate MediaPipe landmark placement.
