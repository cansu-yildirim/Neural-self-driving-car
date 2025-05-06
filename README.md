## Neural Self-Driving Car Simulation (Vanilla JS)

**A fully browser-based, AI-powered self-driving car simulator built entirely with vanilla JavaScript, HTML, and CSS — no external libraries, frameworks, or engines involved.**

This project demonstrates the core concepts of artificial intelligence, neural networks, and evolutionary learning through an interactive 2D simulation. It features a fleet of AI-controlled cars that can perceive their surroundings using virtual sensors, make decisions via a custom-built neural network, and improve over time through an evolutionary algorithm inspired by natural selection.

---

### Features

- **Pure JavaScript implementation**: No external libraries or engines. Everything—from neural networks to ray-casting sensors—is built from scratch.
- **Feedforward Neural Network**: A lightweight, custom-built neural architecture governs each car's behavior.
- **Ray-Casting Sensors**: Simulate LIDAR-like sensor data for detecting road boundaries and obstacles.
- **Evolutionary Algorithm**: Cars learn through random mutation and selection of the best-performing network across generations.
- **Real-Time Neural Network Visualization**: A visual network graph updates live as the top-performing car makes decisions.
- **Customizable Settings**:
  - Car Count
  - Max Speed
  - Mutation Rate
  - Difficulty Level (with persistent localStorage integration)
- **Persistent Learning**: Save and load the best-performing "brain" locally using your browser’s LocalStorage API.
- **Modular File Structure**: Easy to read, extend, and contribute to.

---

### Technologies Used

- **JavaScript (Vanilla)** – Core logic, neural network, simulation, interaction
- **HTML5 Canvas API** – Real-time rendering of the simulation and neural network
- **CSS3 (Flexbox Layout)** – Responsive and structured UI layout
- **LocalStorage API** – Persistent data storage across sessions

---

### Simulation Structure

- **Three-Panel Layout**:
  - **Left**: Settings & Difficulty Controls
  - **Center**: Road & Car Simulation (Canvas)
  - **Right**: Neural Network Visualizer
- **Controls**:
  - `Spacebar`: Reloads simulation with saved settings
  - `Save`: Stores the best brain to LocalStorage
  - `Discard`: Removes saved brain and resets AI
  - `Difficulty Dropdown`: Adjusts challenge level (auto reload)

---

### 🧪 How to Run Locally

```bash
git clone https://github.com/cansu-yildirim/Neural-self-driving-car.git
cd neural-self-driving-car
```

Then simply open `index.html` in your preferred browser:

```bash
open index.html    # macOS
# or
start index.html   # Windows
# or
xdg-open index.html  # Linux
```

---

### 🌱 Future Improvements

- Implement crossover for a true genetic algorithm
- Introduce improved fitness scoring metrics
- Add adjustable sensor ranges and angles
- Optimize rendering performance for large simulations
- Mobile/touch support

---

### Contributing

Pull requests are welcome! If you have suggestions for features, improvements, or find bugs, feel free to open an issue or submit a PR. Let's build something great together!

---

### License

This project is licensed under the [MIT License](LICENSE).  
Free to use, modify, and share with attribution.

---

> **Live Demo:** [Try it here](https://lnkd.in/duw2XEB9)  
> **Source Code:** [GitHub Repository](https://github.com/cansu-yildirim/Neural-self-driving-car)
