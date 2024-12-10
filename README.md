# Dataset

En el codi d'extreuen les dades directament amb un enllanç al dataset.csv d'aquest mateix Github amb la següents linies del codi:
```bash
url = 'https://github.com/sergipadres/PracticaAPA/blob/main/dataset.csv?raw=true'
df = pd.read_csv(url, index_col=0)
```

# Execució i Requisits
D'aquesta manera, simplement executant tot el codi ja es tenen les dades i s'executa tot el codi. 
Per executar aquest projecte, es necessiten les següents biblioteques:
· pandas
· numpy
· scikit-learn
· matplotlib
· seaborn

Podeu instal·lar-les utilitzant pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn  
```
