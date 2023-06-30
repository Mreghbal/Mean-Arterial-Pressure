import tkinter as tk

def calculate_map():
    systolic_bp = float(systolic_entry.get())
    diastolic_bp = float(diastolic_entry.get())
    map_value = (2 * diastolic_bp + systolic_bp) / 3
    map_label.config(text="The Mean Arterial Pressure (MAP) is: {:.2f} mmHg".format(map_value))

# Create the main window
window = tk.Tk()
window.title("MAP Calculator")

# Create systolic BP label and entry
systolic_label = tk.Label(window, text="Systolic BP (mmHg):")
systolic_label.pack()
systolic_entry = tk.Entry(window)
systolic_entry.pack()

# Create diastolic BP label and entry
diastolic_label = tk.Label(window, text="Diastolic BP (mmHg):")
diastolic_label.pack()
diastolic_entry = tk.Entry(window)
diastolic_entry.pack()

# Create calculate button
calculate_button = tk.Button(window, text="Calculate", command=calculate_map)
calculate_button.pack()

# Create result label
map_label = tk.Label(window, text="")
map_label.pack()

# Start the GUI event loop
window.mainloop()
