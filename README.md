Dataset
The dataset includes images of apples with different types of damage, collected from various sources. These damages include:

- Sunburn: Dry, discolored spots on the apple's skin, caused by prolonged sun exposure.
- Reddish Area: Localized discoloration due to physical damage or cryopreservation temperature changes.
- Wound: Breaks or openings in the apple's skin, often allowing microorganisms to enter and accelerate decay.
- Bruise: Contusions or physical damage that result in softened, discolored areas.
- Rotten: Soft, wet, discolored spots caused by fungal or bacterial infections.
- Bitter Pit: Small perforations caused by calcium deficiency during growth.

To create a dataset of apple with the different damages,
repositories such as Kaggle and Roboflow were consulted,
searching with the keywords “Apple", “Damage", “Healthy".
Six datasets were selected with the following names: Ap-
ple Detector Dataset Berserkers (2022), Healthy and Dam-
aged Apples Alhajali (2022), Apple Sorting Dataset Sayidah
(2022), Fruits Fresh and Rotten for Classification R (2022),
Apple2orange Dataset Zhu, Park, Isola and Efros (2017),
and Apple Type Computer Vision Project ennur (2023).
After performing data cleaning, the six damage classes
were grouped due to their similar characteristics, ultimately
resulting in three classes:
■ Class 1: Sunburn, reddish area, and bruise,
■ Class 2: Open wound and bitter pit,
■ Class 3: Rotten.
To balance the number of images per damage class,
another set of apples -with the necessary characteristics- was
purchased. From this new set, approximately 2,000 photos
were taken, varying their orientation and the number of
apples per image.
The complete dataset consisted of 4,000 images divided
into healthy and the three damage classes. Additionally, a
second dataset derived from the first one was collected,
with 1,000 healthy images and 333 images of each of the
aforementioned damage classe
