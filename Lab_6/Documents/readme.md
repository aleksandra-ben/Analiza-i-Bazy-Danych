Section 1: [The contents of the replication documentation]  
Folder Analysis_Data: akrusze kalkulacyjne opracowanych danych (top10_beer_servings.csv, top10_spirit_servings.csv, top10_total_litres_of_pure_alcohol_servings.csv, top10_wine_servings.csv) oraz utworzone na ich podstawie wykresy (top10_beer_servings.png, top10_spirit_servings.png, top10_total_servings.png, top10_wine_servings.png).  
Folder Command_Files: plik wykonawczy Command_file.ipynb.  
Folder Douments: plik readme.md.  
Folder Original_Data: plik oryginalny drinks.csv.  

Section 2: [Instructions for replicating the study]  
Pliki oryginalne przetwarzane były przy pomocy oprogramowania Jupyter Notebook opartego na języku programowania Python3 wraz z bibliotekami matplotlib oraz pandas.  

Plik wykonawczy Command_file.ipynb (folder Command_Files) używa pliku drinks.csv (folder Original_Files). Z arkusza usuwane są rekordy puste, zawierające dane zerowe pominięte w dalszej analizie, a następnie otrzymany arkusz zapisywany jest do używango w dalszej części analizy pliku valid_data.csv (folder Analysis_Data).  

Na podstawie pliku valid_data.csv wyodrębniane są dane dotyczące poszczególnych rodzajów napoju, które następnie sortowane są w kolejności malejącej i obcinane do długości 10 wierszy. Takiej samej procedurze podlega kopia pliku valid_data.csv. Otrzymane dane zapisywane są do plików top10_beer_servings.csv, top10_spirit_servings.csv, top10_total_litres_of_pure_alcohol_servings.csv, top10_wine_servings.csv (folder Analysis_Data). Dla danych tworzone są wykresy słupkowe z nazwami kraju jako etykiety osi x oraz zapisane zostają one do plików top10_beer_servings.png, top10_spirit_servings.png, top10_total_servings.png, top10_wine_servings.png (folder Analysis_Data).  
