# Heatmap 

Heatmap is a data visualization technique

Kaggleda Heatmap üzerinde çalışma yaptım ve opsiyonları tek tek görmeye çalıştım .

. subplots(figsize=(20,10 )

. subplots

. df.corr()

. cmap="Greens" or Reds or Blues or tab20

. annot=True

. fmt= '.3f'

. linewidths=4

. linecolor='orange'

. vmin= -2, vmax= 2

. cbar=0

. square=True

. alpha=0.5  

. shading='gouraud'or auto or nearest or flat 

. xticklabels=False, yticklabels=False

. mask = np.triu(np.ones_like(df_corr, dtype=np.bool_))
mask = mask[1:, :-1]
corr = df_corr.iloc[1:,:-1].copy()

. rotation=45
![Logo](https://blogger.googleusercontent.com/img/a/AVvXsEibHARzG-pjqYzDQQnvsnY4exEnhD3VUZJxfQl--lMaOUBpbc6ygLohR_oz9DkLnA85Z1XN4NA-WF-NWEomv5_f9rrNQeGH23HMXDH-p5I_0AR6eSrDTi-R36tHdGZYU8z9FOF2JDFK1QfLBba6N1sihO0IVg15yjfbBvrlNDpgmh8fPIUo3aNjsoAUpQ)

    
## Link

[Project Link - Kaggle](https://www.kaggle.com/adoger/heatmap-is-a-data-visualization-technique)
