# **Haze User Manual**

This user manual will guide you through the features and functionality of **Haze**, helping you harness its full potential.

Let’s dive in and bring the **haze** to your mix!

---

## **Installation**

For **Mac** and **Windows**, follow these steps to install **Haze**.

- **Mac**:  
  Run `viator-haze-au.pkg` for **AU** plugins or `viator-haze-vst3.pkg` for **VST3** plugins.

- **Windows**:  
  Run `viator-haze-setup.exe`. If you see an **"Unknown Publisher"** warning, click **"More info"** to proceed.

---

## **Signal Flow**

The signal processing in **Haze** follows this order:

**Input → Saturation → Wow & Flutter → Delay → Output**

---

## **Main Controls**

### **Saturation**

Tape saturation is a form of **analog-style harmonic enhancement** that emulates the warmth and character of recording to magnetic tape. 
When audio is driven into a tape machine, the medium naturally compresses transients, rounds off harsh peaks, and introduces subtle harmonic distortion. 
This results in a **rich, musical tone** that makes digital recordings sound **warmer and more organic**.

In **Haze**, the saturation feature recreates this effect by introducing controlled harmonic distortion, soft compression, and a natural-sounding frequency response. 
Depending on the **input level** and **settings**, saturation can add anything from a slight warmth to a **vintage-style coloration**.

**Haze has five controls for shaping the saturation effect:**

1. **Drive**  
   Adjusts the **input gain** into the saturation algorithm.  
   Higher values increase the intensity of distortion, adding warmth and rich harmonics.

2. **Volume**  
   Controls the level of the **wet (saturated) signal**, allowing you to manage gain staging and maintain balance in your mix.

3. **Mix**  
   Blends the processed and dry signals, letting you find the perfect balance between **clean** and **saturated** tones.

4. **Tone**  
   A **low-pass filter** applied **before** saturation. Lowering the cutoff helps tame excessive brightness, preventing harsh distortion.

5. **Compress**  
   Enables a **post-saturation compressor**, mimicking the natural compression that occurs when overdriving a tape machine.

---

### **Wow & Flutter**

**Wow & Flutter** are pitch and timing variations caused by imperfections in tape playback mechanisms. These fluctuations add movement and a natural, vintage feel to audio.

In **Haze**, Wow & Flutter simulates these classic tape irregularities, adding **controlled pitch modulations** to create an analog-style **warmth and depth**.

**Haze has five controls for shaping the wow & flutter effect:**

1. **Wow Rate**  
   Controls the **speed** of the slow pitch modulations.

2. **Wow Depth**  
   Adjusts the **intensity** of the wow effect.

3. **Flutter Probability**  
   Sets the **probability (0–100%)** of flutter occurring.

4. **Flutter Depth**  
   Defines the **intensity** of fast, high-frequency pitch variations.

5. **Mix**  
   Balances the processed and dry signals, letting you dial in subtle or extreme modulation.

---

### **Tape Delay**

**Haze** features a **tape-style delay**, modeled after classic analog delay units, providing warm and natural repeats that degrade smoothly over time.

**Haze has five controls for shaping the tape delay effect:**

1. **Time**  
   Sets the delay time in **milliseconds or beats**, depending on the **Sync** button state.

2. **Feedback**  
   Controls how much of the delayed signal is **fed back into the delay line**, determining the number of repeats.

3. **Mix**  
   Blends the delayed signal with the dry signal.

4. **Sync**  
   Toggles the **Time** control between **milliseconds** and **beat-synced** delay timing.

5. **Spread**  
   Offsets the right delay signal slightly to create a **wider stereo image**.

---

## **Additional Features**

### **1. A/B Presets**
- Save and **switch between two local snapshots** of your settings.
- Easily **compare different configurations**.
- Any changes made after selecting **A** or **B** are automatically saved.

### **2. Presets**
- The **global preset manager**, where you can **save, browse, and load** custom or factory presets.
- Quickly recall your favorite settings or **explore new tones**.

### **3. Stereo Menu**
- Select the desired **processing mode**:
    - **Stereo**: Processes and outputs the signal normally.
    - **Mono**: Sums the stereo signal to mono for **centered processing**.
    - **Mid**: Applies processing to the **mid (center)** part of the stereo field.
    - **Side**: Processes only the **side (stereo width)** signals.

### **4. HQ Menu**
- Choose the level of **oversampling** (**Off, 2x, 4x, 8x, 16x**).
- Higher oversampling rates reduce aliasing but increase **CPU usage**.

### **5. Power Button**
- Toggles the **audio processing on or off**, allowing you to bypass the plugin.

### **6. Info Menu**
- Access essential resources, including:
    - **Support links**
    - **User manual**
    - **Discord server**
    - **Support email**
    - **End User License Agreement (EULA)**

---

## **Tooltips**

At the bottom of the plugin interface, you’ll find a **dynamic tooltip area**.

- **Hover over a control** to display a **brief description** of its function.
- The **tooltip disappears** when you move your cursor away, keeping the interface clean and clutter-free.
