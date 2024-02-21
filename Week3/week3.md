## Days 1 to 5

### This week we worked on camera architectur 

The types of cameras that are used in satellites.

Optical Cameras: These traditional cameras capture visible light reflected off objects. Their range is limited by object size, reflectivity, and atmospheric interference. While high-altitude satellites can see further due to less atmosphere, the practical limit for detailed images of objects on Earth is typically below 1000 km.


Basic Architecture:
Lens: Focuses incoming light onto the sensor.
Image Sensor: Converts light into electrical signals, capturing color and intensity information.
Filter Array: Usually a Bayer filter, divides incoming light into specific colors (red, green, blue) for color images.
Image Processor: Processes raw sensor data, performing tasks like noise reduction, color correction, and image sharpening.
Storage: Saves captured images for later viewing or transfer.
Focus on Visible Light: Utilizes the visible light spectrum reflected off objects to create images.
Strengths:
High resolution and detailed images.
Good at capturing color and texture information.
Relatively simple and affordable technology.
Weaknesses:
Limited range due to reliance on reflected light.
Affected by atmospheric conditions and lighting.
Not suitable for imaging through clouds or darkness.








Remote Sensing Cameras: These utilize different wavelengths like radar or lidar to create images. Radar can "see" through clouds and darkness, offering broader range, but with lower resolution and detail compared to optical cameras. Specialized radar satellites can map Earth's surface from much higher orbits (e.g., 20,000 km), but the imagery may not be directly recognizable as "pictures."
https://opg.optica.org/ao/abstract.cfm?uri=ao-62-8-C88 


Diverse Architectures:
Optical Sensors: Similar to optical cameras for capturing visible light, but often with specialized filters or configurations.
Non-Optical Sensors: Utilize other parts of the electromagnetic spectrum (radar, lidar, thermal) to gather information beyond visible light.
Complex Processing: Data processing and interpretation are crucial to convert sensor signals into meaningful images or information.
Beyond Visible Light: Capture data using various wavelengths beyond visible light, enabling imaging through obstacles like clouds and darkness.
Strengths:
Broader range and ability to "see" through obstacles.
Provide unique information about object properties beyond just visual appearance (e.g., temperature, elevation).
Valuable for applications like weather forecasting, mapping, and resource exploration.
Weaknesses:
Generally lower resolution and detail compared to optical cameras.
Images might require complex processing and interpretation for understanding.
More expensive and complex technology than basic optical cameras.




Key Differences:
Sensor Technology: Optical cameras rely on light sensors, while remote sensing cameras use diverse sensors for various wavelengths.
Information Captured: Optical cameras capture visual information, while remote sensing cameras capture a wider range of data beyond just visual appearance.
Strengths and Weaknesses: Each type has unique advantages and limitations depending on the application and desired information.




Increasing the range of camera ➖
Optical System Design:
Example: Suppose you're designing a satellite with a high-resolution camera to observe Earth's surface. You might employ a larger primary mirror or a more sophisticated lens system. For instance, the Hubble Space Telescope utilizes a 2.4-meter primary mirror, enabling it to capture incredibly detailed images of distant celestial objects.
Advanced Imaging Sensors:
Example: Consider using a sensor like the Charge-Coupled Device (CCD) or Complementary Metal-Oxide-Semiconductor (CMOS) with improved sensitivity and dynamic range. These sensors can capture clearer images even in low-light conditions or when imaging distant objects. For instance, the HiRISE camera on NASA's Mars Reconnaissance Orbiter uses a CCD sensor with enhanced sensitivity to capture high-resolution images of the Martian surface.
Telescopic Systems:
Example: Implementing a telescopic system allows for variable focal lengths, enabling the satellite to zoom in on distant objects. For example, the GeoEye-1 satellite features a telescope with a focal length of 1.1 meters, enabling it to capture high-resolution images of Earth's surface from a distance of over 680 kilometers.
Image Processing Algorithms:
Example: Employ sophisticated algorithms onboard the satellite to enhance captured images. For instance, super-resolution imaging techniques combine multiple low-resolution images to create a single high-resolution image. NASA's Juno spacecraft uses such algorithms to enhance the resolution of images captured of Jupiter's atmosphere from a distance of over 600 million kilometers.
Satellite Orbits:
Example: Optimize the satellite's orbit to maximize its visibility and coverage area. Placing the satellite in a low Earth orbit (LEO) reduces the distance to the target area, enabling clearer imaging. The International Space Station (ISS), orbiting at approximately 400 kilometers above Earth's surface, captures detailed images of Earth's surface with its cameras.
Data Transmission and Storage:
Example: Upgrade data transmission and storage capabilities to handle large volumes of data. For instance, the Landsat series of satellites capture vast amounts of Earth observation data, which is transmitted to ground stations using high-bandwidth communication systems for processing and analysis.
Power and Thermal Management:
Example: Ensure the satellite has sufficient power and effective thermal management. The Solar Dynamics Observatory (SDO) utilizes solar panels to generate power and advanced thermal control systems to manage the heat generated by its imaging instruments, enabling it to capture high-resolution images of the Sun from a distance of over 150 million kilometers.






Image Processing Algorithms used in satellite cameras
Radiometric Calibration: This algorithm corrects variations in sensor sensitivity and removes sensor noise, ensuring consistent radiometric values across the image. It helps in maintaining accurate brightness and color levels in satellite images.
Geometric Correction: Geometric correction algorithms correct distortions caused by factors like satellite attitude changes, Earth's curvature, and terrain relief. These corrections ensure that the image accurately represents the Earth's surface.
Orthorectification: Orthorectification algorithms remove perspective distortions caused by variations in terrain elevation. By geometrically rectifying the image, they ensure that features are represented in their true geographic locations.
Pan-Sharpening: Pan-sharpening algorithms combine high-resolution panchromatic (black and white) imagery with lower-resolution multispectral (color) imagery to create a single high-resolution color image. This enhances the spatial detail of the multispectral image.
Image Fusion: Image fusion algorithms combine images from different sensors or spectral bands to create composite images with enhanced information content. For example, combining thermal infrared imagery with visible imagery can provide insights into environmental phenomena like urban heat islands.
Super-Resolution: Super-resolution algorithms enhance the resolution of satellite images by synthesizing higher-resolution images from multiple lower-resolution images of the same scene. This helps in capturing fine details not visible in individual images.
Feature Extraction: Feature extraction algorithms identify and extract specific features or objects of interest from satellite images. These algorithms can detect objects like buildings, roads, vegetation, and water bodies, facilitating various applications such as urban planning and environmental monitoring.
Change Detection: Change detection algorithms analyze pairs of satellite images captured at different times to identify and quantify changes in land cover, land use, or other environmental factors. This is valuable for monitoring deforestation, urban expansion, and natural disasters.
Cloud and Atmospheric Correction: These algorithms remove the effects of clouds, haze, and atmospheric scattering from satellite images, improving visibility and accuracy. They enable clearer observations of the Earth's surface under varying atmospheric conditions.
Machine Learning and Deep Learning: Machine learning and deep learning algorithms are increasingly being used in satellite image processing for tasks such as image classification, object detection, and semantic segmentation. These algorithms can automatically learn and extract complex patterns and features from satellite imagery, enabling advanced analysis and interpretation.


Advanced Imaging Sensors used in satellite cameras 


Charge-Coupled Device (CCD):
CCD sensors are widely used in satellite cameras for their high sensitivity to light and excellent signal-to-noise ratio. They offer good spatial resolution and are suitable for capturing detailed images of Earth's surface.
Complementary Metal-Oxide-Semiconductor (CMOS):
CMOS sensors are becoming increasingly popular in satellite cameras due to their lower power consumption, faster readout speeds, and reduced complexity. They offer comparable image quality to CCD sensors and are well-suited for applications requiring high-speed imaging.
Hybrid CMOS Sensors:
Hybrid CMOS sensors combine the advantages of both CCD and CMOS technologies, offering high sensitivity, low noise, and fast readout speeds. They are suitable for demanding imaging applications in satellites, such as high-resolution Earth observation and remote sensing.
Charge Injection Device (CID):
CID sensors are specialized imaging devices with low noise and high sensitivity, making them suitable for capturing faint signals in low-light conditions. They are used in satellite cameras for applications such as astronomical observations and night-time Earth imaging.
Staring Array Sensors:
Staring array sensors consist of an array of individual photodetectors, allowing simultaneous capture of multiple image pixels. They offer high spatial resolution and are used in satellite cameras for capturing detailed images of Earth's surface with minimal motion blur.
Pushbroom (Whiskbroom) Sensors:
Pushbroom sensors utilize a scanning mechanism to capture images line by line as the satellite moves along its orbital path. They offer high spatial resolution and are commonly used in satellite cameras for hyperspectral imaging and terrain mapping applications.
Tunable Filter Sensors:
Tunable filter sensors allow selective imaging of specific spectral bands by adjusting the wavelength of light passing through the sensor. They are used in satellite cameras for multispectral and hyperspectral imaging applications, enabling analysis of Earth's surface properties and vegetation health.
Thermal Infrared Sensors:
Thermal infrared sensors detect infrared radiation emitted by objects based on their temperature. They are used in satellite cameras for thermal imaging applications, such as monitoring land surface temperature, detecting wildfires, and assessing urban heat islands.




Currently the camera that is made of all the above tech is WorldView-3 , with a range of 620 kms
Now to increase the range of WorldView-3 we need :- 


Orbital Adjustment:  Move WorldView-3 to a higher orbit with an altitude of around 3000 kilometers. This would increase the range of the satellite, allowing it to capture images of objects from a greater distance. However, this would also affect its ground resolution, as the pixel size would increase with altitude.
Improved Imaging Sensors: Develop and install more sensitive and higher-resolution imaging sensors on WorldView-3 to compensate for the increased distance to the Earth's surface. These sensors should be capable of capturing clear and detailed images from a greater range.
Optical System Enhancements: Upgrade the optical system of WorldView-3 to improve its resolving power and magnification capabilities. This may involve using larger primary mirrors or lenses with higher precision to capture detailed images of objects from a greater distance.
Telescopic Systems: Implement telescopic systems onboard WorldView-3 to extend its range. Telescopic systems allow the satellite to zoom in on distant objects, capturing images with greater clarity and detail even from longer distances.
Data Transmission and Storage: Upgrade the satellite's data transmission and storage capabilities to handle the larger volumes of data generated by capturing images from longer distances. This involves implementing efficient compression algorithms and utilizing high-bandwidth communication systems.
Power and Thermal Management: Ensure that WorldView-3 has sufficient power and effective thermal management systems to support the operation of its imaging components over longer distances. Higher resolution cameras and advanced imaging systems may require more power and generate more heat, so optimizing these systems is essential.
Propulsion System Upgrade: Equip WorldView-3 with a more powerful propulsion system capable of adjusting its orbit to the desired altitude of 3000 kilometers. This would enable the satellite to reach and maintain the higher orbit required for increased range.
Collaborative Efforts: Collaborate with other organizations, such as research institutions or private companies, to access cutting-edge technologies and expertise that can further enhance the range of WorldView-3.
In this type of camera arch we need to improve the orbit placement , image processing algorithms 
