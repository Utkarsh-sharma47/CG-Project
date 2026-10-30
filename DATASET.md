# Gerrard Hall sample

The photos and the sample sparse model are not stored in this repository.
`gerrard-hall.zip` is 959 MB, and the included `database.db` files are over
GitHub's 100 MB file limit. The files stay on COLMAP's official download.

Dataset page: https://demuc.de/colmap/datasets/

Direct archive, confirmed from that page:

https://github.com/colmap/colmap/releases/download/3.11.1/gerrard-hall.zip

Size: 1,005,335,375 bytes.

Download and extract it next to a clone:

```bash
mkdir -p demo
curl -fL -o demo/gerrard-hall.zip \
  https://github.com/colmap/colmap/releases/download/3.11.1/gerrard-hall.zip
unzip demo/gerrard-hall.zip -d demo
```

The archive extracts to `demo/gerrard-hall/`:

- `images/` — 100 photos, `IMG_2331.JPG` through `IMG_2430.JPG`
- `sparse/` — the sample sparse point cloud shipped with the dataset
- `database.db` — the sample feature database shipped with the dataset

This sample is part of the COLMAP datasets published by Johannes Schönberger.
COLMAP itself remains under the BSD license in `LICENSE`.
