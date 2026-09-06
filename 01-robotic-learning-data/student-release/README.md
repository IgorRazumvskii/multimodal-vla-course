# Laboratory: Robot Learning Data & Action Spaces

This folder contains everything required to complete the laboratory work:

```text
student-release/
├── README.md
├── seminar_01_data_and_actions.ipynb
└── data/
    └── lerobot_v3/
```

The dataset contains four synthetic SO-ARM100 episodes in LeRobotDataset v3.0 format. The
notebook reads it locally; no simulator, Hugging Face account or dataset download is required.

## Environment setup

Use Python 3.11. From this folder, create and activate a virtual environment:

```bash
python3.11 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install "lerobot==0.4.3" numpy pandas matplotlib pillow jupyterlab
python -m jupyter lab seminar_01_data_and_actions.ipynb
```

On Windows, activate the environment with:

```powershell
.venv\Scripts\activate
```

Keep the notebook and the `data/lerobot_v3` directory in their current relative locations.

## What to do

Complete the work independently and run the notebook from top to bottom.

1. Replace every `TO DO` and `NotImplementedError` with your implementation.
2. Run the checks after each exercise and fix your code if a check fails.
3. Answer every question in a **Your task** cell using the values, tables and plots produced by
   your run.
4. Restart the kernel and run the completed notebook from the beginning.
5. Make sure the final notebook contains your code, written answers and cell outputs.

## Submission

Save the completed notebook and send `seminar_01_data_and_actions.ipynb` to the instructor.
The submitted file must contain all implementations, answers and generated outputs.
