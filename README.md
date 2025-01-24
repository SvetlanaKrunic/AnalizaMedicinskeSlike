# AnalizaMedicinskeSlike
 Projekat za predmet Analiza Medicinske Slike na ftnuns

**Cilj:**
Cilj je veoma jednostavan, detekcija ili segmentacija nečeg što je anotirano na tim slikama.

**Baze:**
Baze koje je prof Tatjana Loncar Turukalo preporučila:
1. https://www.i3s.up.pt/digitalpathology/
2. https://github.com/MindLab-DP/Datasets 

**Njeni saveti:**
- Histopatoloske slike imaju oko 1 do 5GB svaka.
- Treba ti potpuno anotiran skup, što je dosta zahtevno.
- Nije loše izabrati neki skup gde imas bar bounding box anotacije.
- Ako imas anotacije na nivou jedne slike, koje su jako velike, 
  onda imamo problem kada sečeš slike da ne znamo da li je u svim segmentima slike 
  zahvaćeno sa tom nekom promenom ili vrstom ćelija.
- Te slike su izuzetno specifične i vredi isprobati ceo pipeline na njima. 
  Hardverski ce to takodje biti zahtevno, ali imamo svoje kapacitete.

**Izvori sa prethodnih projekata na katedri:**
Ako se sećaš pričala sam ti o nekoj grupi iz Finske koja je sa nama radila na prethodnom projektu. 
Evo šta oni imaju. Kopiram iz deliverable:
"the PanNuke (Gamper, et al., 2020) comprehensive datasets including digitalized histopathological images from different tissue types, as well as the corresponding annotated nuclei with their class labels"
Gamper, J., Koohbanani, N. A., Benes, K., Graham, S., Jahanifar, M., Khurram, S. A., . . . Rajpoot, N. (2020). PanNuke Dataset Extension, Insights and Baselines. ArXiv.


performance metrics "Benchmark metrics commonly used to evaluate the performance of instance segmentation models are segmentation quality (SQ), detection quality (DQ) and panoptic quality (PQ). These image analysis performance metrics are defined as follows (Kirillov, He, Girshick, Rother, & Dollar, 2019):"
Kirillov, A., He, K., Girshick, R., Rother, C., & Dollar, P. (2019). Segmentation, Panoptic. IEEE/CVF Conference on Computer Vision and Pattern Recognition, 9404-9413


Rad koji su ti Finci objavili je:
Ariotta, V., Lehtonen, O., Salloum, S., Micoli, G., Lavikka, K., Rantanen, V., . . . Hautaniemi, S. (2023). H&E image analysis pipeline for quantifying morphological features. Journal of Pathology Informatics, 14. doi:doi.org/10.1016/j.jpi.2023.100339