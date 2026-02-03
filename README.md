# ACL mechanotransduction – 3D signaling cascade

This project builds a mechanotransduction signaling cascade relevant to ACL/ligament cells
and visualizes it as an interactive 3D network and a 3D ACL schematic.


---

## How to run (Google Colab)

1. Open `notebooks/ACL_mechanotransduction_3D.ipynb` in **Google Colab**
2. Run all cells from top to bottom
3. Outputs:
   - `data/acl_mechanotransduction_nodes.csv`
   - `data/acl_mechanotransduction_edges.csv`
   - `outputs/acl_mechanotransduction_3d.html`

---

## Regime mode (physiological vs overload)

Inside the notebook you can display:
- full network: `regime="both"`
- adaptive: `regime="physio"`
- overload/injury: `regime="overload"`

---

## Dependencies

- numpy
- pandas
- networkx
- plotly
- py3Dmol (optional)
- requests (optional, for downloading PDB)

---

## License
MIT

---

## Citation / Disclaimer
This is a research-education visualization tool and **not** a clinical decision system.  
Pathways are simplified and curated for interpretability.
