![360_F_43028992_xoR6s9egyaM9oTXV4yXtDtg3tWIkPsgC](https://github.com/JessemanGray/GraphUp/assets/123507565/aadb0335-463c-47d9-9be6-8bdd2a4beaec)
# GraphUp
They say there are two seasons in a big city, winter and construction...

GraphUp is intended to be a lightweight dashboard for viewing MEP (mechanical, electrical, and plumbing) 3d renderings. The app can display multiple windows for different floors or zones, and it has modest interactive functionality with sliders to view different layers. 

Future improvements will include more complex measurement labels and informatics, as well as being accessible by mobile device through an API.

Installation & Usage

GraphUp is currently Under Construction, but a Colab notebook is included in this repository as a template. Readily available standard imports along with plotly, open3D, and Dash complete the setup, and some .ply models are available in this repository as well.

To modify notebook to users' preference, simply load a ply, obj, or off model into the 'model_path' variable, and the open3d, plotly, and dash components will render the 3D model in a datapoint driven graphical interface. Some parameters may need to be adjusted to achieve optimal results. 

Multiple layers can be overlayed and the opacity adjusted with slider bars in the dashboard area.

Please note: Using Google Colab allows for a rapid prototyping process, but there are still quite a few issues to debug before being able to reliably reproduce images in a Flask app. These features will be added to updated versions oin the near future.

Currently this app has a few quirks and can only be used on a surface level for visualizing architectural models. Other interesting applications beyond construction could be to create virtual 'memory palaces' to improve cognitive performance, visualization of complex data architectures, world-building, and training for inspections and emergency personel.

Contributions

Please feel free to fork and use existing template

![Alt Text](https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif)


