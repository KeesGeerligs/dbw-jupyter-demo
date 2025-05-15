# How to Use Nosana

This project allows you to run a Jupyter Notebook on a GPU-enabled container using the Nosana platform.

## Instructions

1.  **Go to the Nosana Dashboard:**
    Open your web browser and navigate to [https://dashboard.nosana.com/deploy](https://dashboard.nosana.com/deploy).

2.  **Use the Advanced Builder:**
    *   Locate the "Advanced Builder" section on the page.
    *   Copy the contents of the `job-definition.json` file from this repository.
    *   Paste the copied JSON content into the Advanced Builder.

3.  **Configure and Run:**
    *   Select a GPU for your job.
    *   Click the button to run the job.

4.  **Access Jupyter Notebook:**
    *   Once the job is running, Nosana will provide a service URL.
    *   Open this service URL in your web browser. This will open the Jupyter Notebook web interface.
    *   Upload your `.ipynb` notebook file into the Jupyter Notebook interface.
    *   Open the uploaded notebook and run your cells.

Enjoy your GPU-powered Jupyter Notebook! 