WORK-IN-PROGRESS

# SO-110

## Grippers

### 1. Parallel Gripper

The following gripper is a modified version of the base gripper that was designed by @norma-core (for full design and details: <https://github.com/norma-core/norma-core/blob/main/hardware/pgripper/README.md>).

This version includes several design modifications:

* Changed the shape, size, and length of the jaws to better handle small objects. The grasping point was also elevated closer to the camera for improved visibility.

* Added a mounting point on the gripper's base to support a bottom camera.

* Added notches on the inside of the jaws to support mouting arcs that can be used to grasp cylinderical tools (e.g. screw driver). See the "attachments" section.

<p>
  <img src="images/gripper-side.jpeg" alt="preview" width="200" height="240" style="display:inline-block; margin-right:8px;">
  <img src="images/gripper-top-down.jpg" alt="preview" width="200" height="240" style="display:inline-block; margin-right:8px;">
  <img src="images/gripper-top-side.jpg" alt="preview" width="200" height="240" style="display:inline-block;">
</p>

The design .stl files can be found [here.](hardware/modified_gripper)

## Attachments

### 1. Height and tilt-adjustable wrist camera mounts

https://github.com/user-attachments/assets/957fd91d-6abd-45eb-9cc1-369022933ae7

#### Note: this is designed for the InnoMaker USB 2.0 UVC camera (or cameras with similar dimensions where the distance between the holes is 28mm). If you need help with adapting to other cameras, please open an issue on this repo.

#### 1.1. Top camera mount

<table border="1">
  <tr>
    <th>Parts</th>
    <th>Quantity</th>
    <th>Links</th>
    <th>Notes</th>
  </tr>
  <tr>
    <td>3D printed parts</td>
    <td>x1</td>
    <td><a href="designs/cameras/top_camera_mount.stl">.stl file</a></td>
    <td></td>
  </tr>
  <tr>
    <td>InnoMaker Camera</td>
    <td>x1</td>
    <td><a href="https://www.amazon.com/innomaker-Computer-Raspberry-Support-Windows/dp/B0CNCSFQC1?sr=8-3">720p - Amazon</a>, <a href="https://www.amazon.com/innomaker-Computer-Raspberry-Support-Windows/dp/B0CLRJZG8D?sr=8-4">1080p - Amazon</a></td>
    <td>For other cameras, see the note above.</td>
  </tr>
  <tr>
    <td>M3 x 16mm Hex Socket screws</td>
    <td>x4</td>
    <td><a href="https://www.amazon.com/dp/B0FG2BRXL3">Assortment kit - Amazon</a></td>
    <td>Holds the camera in place</td>
  </tr>
  <tr>
    <td>M3 x 30mm Hex Socket screws</td>
    <td>x1</td>
    <td>Same kit</td>
    <td>For the hinge connecting the two pieces</td>
  </tr>
  <tr>
    <td>M3 Hex Socket nuts + washers</td>
    <td>x5</td>
    <td>Same kit</td>
    <td>For the screws above</td>
  </tr>
</table>

#### 1.2. Bottom camera mount

<table border="1">
  <tr>
    <th>Parts</th>
    <th>Quantity</th>
    <th>Links</th>
    <th>Notes</th>
  </tr>
  <tr>
    <td>3D printed parts</td>
    <td>x1</td>
    <td><a href="designs/cameras/bottom_camera_mount.stl">.stl file</a></td>
    <td></td>
  </tr>
  <tr>
    <td>InnoMaker Camera</td>
    <td>x1</td>
    <td><a href="https://www.amazon.com/innomaker-Computer-Raspberry-Support-Windows/dp/B0CNCSFQC1?sr=8-3">720p - Amazon</a>, <a href="https://www.amazon.com/innomaker-Computer-Raspberry-Support-Windows/dp/B0CLRJZG8D?sr=8-4">1080p - Amazon</a></td>
    <td>For other cameras, see the note above.</td>
  </tr>
  <tr>
    <td>M3 x 16mm Hex Socket screws</td>
    <td>x4</td>
    <td><a href="https://www.amazon.com/dp/B0FG2BRXL3">Assortment kit - Amazon</a></td>
    <td>Holds the camera in place</td>
  </tr>
  <tr>
    <td>M3 x 30mm Hex Socket screws</td>
    <td>x1</td>
    <td>Same kit</td>
    <td>For the hinge connecting the two pieces</td>
  </tr>
  <tr>
    <td>M3 Hex Socket nuts + washers</td>
    <td>x5</td>
    <td>Same kit</td>
    <td>For the screws above</td>
  </tr>
</table>

### 2. Extras

#### 2.1. Arcs for screwdrivers

## Credits

* I worked on the designs and modification in collaboration with @dotdotdotquestionmark (swang[at]stanleywang[dot]me).
* Parallel-jaws gripper original design: @norma-core
