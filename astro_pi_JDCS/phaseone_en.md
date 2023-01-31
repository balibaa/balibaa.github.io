# Phase 1 - idea submission

## Comparing regulated environments

The aim is to gather data from the various sensors on the ISS during the 3 hours, look at fluctuations, min-max values and averages. Check, what is the minimum amount of sample needed for the various sensors, to come to a good estimated average. Lower fluctuation is expected for temperature, humidity and pressure. Gyroscope and magnetic sensor are expected to provide predictable values. Accelerator most probably affected by (not predictable) crew interaction.

The 3 hours allow by plan over 10000 pcs of 1 second interval samples.

**Compare sample values of:**

* total experiment (all one second interval samples)
* 5 minutes interval samples
* 1 minute interval samples
* 1 second interval samples
* some short but "max-speed possible" samples based on interaction (crew proxymity) or "no crew proximity" parts of the experiment. Expectation is to be able to find an "ideal" sample rate for the different sensors, that would produce the same averaged results, like the whole experiment did. This could improve efficiency planning of future experiments.

Using the PIR and the color and luminosity sensors, **try to identify astronauts** and find corellation between temperature, accelerometer (these two are expected). Check, if there are other sensor value changes, that might be connected to crew proximity. Using the camera (probably light reflection) try to confirm the predicted astronaut (using the coral accelerator). Display different led images for differently identified crew proximity.

**Display different led images** for differently identified crew proximity. Check if vibrating/flashing images cause astronauts to look at the display longer. (You might want to cancel this, we certainly don't want to distract the crew. The hypothesis is, that maybe they would look at the display (longer) if it produces some unexpected flashing, when they approach.)

Once the finalized experiment ran on the ISS, **run the same experiment on Earth**, using the kid's "regulated environments" of choice. The idea is to run the same experiment with the same expectations (except traveling around the earth certainly) and compare the end results. Which is a more stable environment? Where were the participants longer in proximity of the PI.

**Current ideas of where the experiment could be reproduced:**

* at school
* at the pet zoo
* at scout camp
* during a train journey
* in the library
* in the park
* one night at the terrace (cat interaction expected :)
* in the kitchen at home (the kid's are all sisters/brothers)

## Data

**Sensor values at regular intervals:** (1 second is proposed, 10000 cycles expected to complete during the experiment.)

**Sensor data at maximum sample speed:** for short intervals at least 20 times based on interaction (crew proximity) and 20 times when there is no interaction (silent times).

**Comparison of crew identification using the color sensor and the camera:** using reflected light analysis when there's a motion detection. (Please let us know, if you think this is impossible, it sounds like a good idea, but maybe the hardware setup does not allow this.)

**+1. The same datasets replicated in the various "on earth" experiments:** Analysis might concentrate at ISS data only in the end, but the overall goal would be to compare the fluctuations and compare the "ideal sample rates" in the different environments.

## Machine Learning Usage

Our plan is to try to identify individuals based on their difference in reflected light (color of clothing mostly probably) and temperature.
