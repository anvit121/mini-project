# Instagram Likes Prediction - Mini Project

## Files

- `code.ipynb`: analysis, code and plots
- `report.pdf`: findings
- `presentation.pptx`: presentation
- `test_predictions.csv`: predictions from the recorded run
- `requirements.txt` and `requirements-torch.txt`: dependencies

## Setup

Install Python 3.13 and Git and then run these commands in the project folder:

```powershell
py -3.13 -m venv .venv
.\.venv\Scripts\python.exe -m pip install --upgrade pip setuptools wheel
.\.venv\Scripts\python.exe -m pip install -r requirements-torch.txt --index-url https://download.pytorch.org/whl/cpu
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

For an NVIDIA GPU, replace `/cpu` with `/cu128`

Put the CSV file in `data/instagram_data.csv` and the images in `data/insta_data/`

## References

- [OpenAI CLIP](https://github.com/openai/CLIP)
- [PyTorch installation](https://pytorch.org/get-started/locally/)
- [Papers Explained - CLIP](https://ritvik19.medium.com/papers-explained-100-clip-f9873c65134)
- [What exactly is a Vision Transformer?](https://vizuara.medium.com/what-exactly-is-a-vision-transformer-a017e845c03e)
- [K-means Clustering Clearly Explained](https://medium.com/@luo9137/k-means-clustering-clearly-explained-44746ccc3621)
- [Understanding Random Forest - Tony Yiu](https://medium.com/towards-data-science/understanding-random-forest-58381e0602d2)
- [Log Transformations in Linear Regression - Samantha Knee](https://medium.com/swlh/log-transformations-in-linear-regression-the-basics-95bc79c1ad35)
- [What are RMSE and MAE? - Shwetha Acharya](https://medium.com/data-science/what-are-rmse-and-mae-e405ce230383)