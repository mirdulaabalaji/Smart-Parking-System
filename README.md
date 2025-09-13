# Smart-Parking-System

The Parking Space Detection System is a computer vision–based application designed to automatically detect available parking spaces from video feeds in real time and provide users with an interactive web-based map for visualization. The system integrates image processing, object detection, and mapping technologies to simplify parking management and improve efficiency in crowded parking areas.

By analyzing live or recorded surveillance footage of parking lots, the system continuously monitors parking occupancy and updates the status of each space. The results are then displayed on an interactive map, allowing users to easily identify available parking spaces and calculate distances to them.

## Key Features

- Parking Space Detection:
Uses computer vision techniques to identify and monitor the occupancy status of each parking slot in video feeds.

- Real-Time Tracking:
Continuously updates parking availability as vehicles enter or leave.

- Interactive Web Map:
Visualizes parking spaces on an HTML-based interactive map (interactive_parking_map.html), where users can view availability.

- Distance Calculation:
Computes distances to available parking spaces to help users choose the most convenient slot.

- Multi-Video Support:
Implemented on three different sample parking lot videos (carPark.mp4 and two additional test videos) to ensure adaptability across different scenarios.

## Project Structure

```
├── ParkingSpace.py               # Core parking space detection logic (implemented separately for 3 videos)
├── interactive_map.py            # Map interface for visualizing parking spaces
├── main_with_interactive.py      # Main application entry point
├── carPark.mp4                   # Sample video feed (3 different videos used for testing)
└── interactive_parking_map.html  # Generated web-based interactive parking map
```

## Applications

- Smart parking management systems in shopping malls, airports, and public parking lots.
- Urban traffic control systems to reduce congestion caused by parking searches.
- Real-time assistance for drivers through mobile/web interfaces.


Acknowledgement : Murtaza's Workshop. Learnt the Parking Space Detection logic with his youtube video.
