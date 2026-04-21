CIFAR-10 Image Classification (CNN)

Tento projekt obsahuje implementaci konvoluční neuronové sítě (CNN) v prostředí TensorFlow/Keras pro klasifikaci obrázků z datasetu CIFAR-10. Model byl navržen a odladěn tak, aby dosáhl vysoké přesnosti bez použití transfer learningu (předtrénovaných modelů).

Testovací přesnost (Accuracy): 89 %

Trénovací přesnost: 90 %

Klíčové vlastnosti:

    Custom Architecture: Vlastní hluboká CNN postavená na blocích konvolučních vrstev.

    Regularizace: Efektivní využití Dropoutu, Batch Normalization a GlobalAveragePooling2D pro stabilitu a potlačení overfittingu.

    Data Augmentation: Implementace náhodných rotací a překlápění pro zvýšení robustnosti modelu.

    Dynamic Learning Rate: Využití callbacku ReduceLROnPlateau pro automatické ladění učícího tempa během tréninku.

    Vizualizace: Generování matice záměn (Confusion Matrix) a logování do TensorBoardu.
