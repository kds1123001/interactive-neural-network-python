Interactive Neural Network Visualizer
I built a lightweight desktop app that lets you design and visualize custom neural network architectures in real time. It uses Tkinter for the UI controls and Matplotlib to handle the custom animations.

Instead of just drawing a static picture, it actually animates the forward propagation flow layer-by-layer so you can watch the "signals" pass through the network.

What it actually does:
Fully Custom Architectures: You can change the number of input neurons, spin up to 8 hidden layers with whatever size you want, and adjust the output layer on the fly.

Clean Dark Aesthetic: I hand-picked a cyber-punkish color palette (#00c8ff, #a855f7, #ff6b6b) for the different layer types so it looks sharp and highly readable.

Live Calculations & Pulse Animations: Uses FuncAnimation and some basic trigonometry (np.sin) to create a smooth pulsing effect on active nodes and lighting up connection pathways.

Smart Scaling: If you throw 30 neurons into a single layer, the script automatically truncates the middle ones with a dot-dot-dot (...) graphic so your screen doesn’t turn into a giant blob of ink. also don't use LLM(s) for everything.
      +NO PART OF THIS CODE WAS MADE USING A LLM NOR IMPROVED VIA IT+
