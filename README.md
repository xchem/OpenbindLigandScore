# OpenbindLigandScore
A repository for scoring partial occupancy ligand builds against PanDDA maps

```
python ligand_score.py --mtz_path=<path to mtz> --zmap_path=<path to pandda z map> --ligand_id=<"chain"/"insertion id"> --structure_path=<path to structure to score> --out_path=<path to output text file> --f=<f column to calculate xmap> --phi=<phi column to calculate xmap>

```