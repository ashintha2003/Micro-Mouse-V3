# Micro Mouse V3

## Team Members

Ashintha, Dulaj, Lakna, Yeisth, and Gamunu

## About

This is the latest micro-mouse that we developed.

I designed and implemented the entire firmware, including:
- Flood Fill algorithm for maze-solving logic
- PID controllers for accurate motor control
- Sensor calibration for reliable wall detection and tracking

### Key Features

- **Four-Wheel Micro-Mouse Design**  
  Built according to the standard specifications used in official micromouse competitions.

- **Powered by ESP32-S3**  
  Utilizes the dual-core architecture of the ESP32-S3:
  - **Core 1** is dedicated to running the Flood Fill algorithm for path planning.
  - **Core 0** handles the real-time PID control algorithms for motor speed and direction.

- **PID Algorithm Tuned Using MATLAB**  
  The PID control logic was modeled and fine-tuned in MATLAB for optimal performance in navigating the maze.

This micro-mouse combines real-time embedded systems, control theory, and efficient pathfinding to deliver fast, intelligent maze-solving performance.




## Images of the micro mouse 

<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/51cc0d1e-67b7-4f0a-93cc-c29141bce7d2" alt="Screenshot 1" width="400"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/b6bbc9a5-227c-4ca8-9869-5d8906799257" alt="Screenshot 2" width="400"/>
    </td>
  </tr>
</table>

## Results
### MATLAB PID TUNING 

<table>
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/fbe3f84a-11e7-4011-8649-263cc3d091c6" alt="Screenshot 1" width="300"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/aa87dc0f-6408-4a7b-8f91-3927877416fe" alt="Screenshot 2" width="300"/>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/0402b8bd-96e5-49e6-8006-7f021a002f69" alt="Screenshot 3" width="300"/>
    </td>
  </tr>
</table>

### Flood fill algorithm simulation using Java 

![Screenshot 2025-05-18 224527](https://github.com/user-attachments/assets/cbf6c498-dd2a-4544-aa2d-5fa963b2b4e0)


### Videos of the micro mouse  

### fine PID tune
https://github.com/user-attachments/assets/c952440c-e476-4505-826e-5273c2423a68
### Results


















