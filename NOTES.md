## 5 W + 1
- **WHO**: Partolini S.R.L
- **WHAT**: Ha consegnato una quantità di bottiglie inferiore rispetto all'accordo
- **WHEN**: ?
- **WHY**: Possibile truffa o errore umano?
- **WHERE**:
- **HOW**:

## Forensic Tools
- FTKImager: https://www.exterro.com/digital-forensics-software/ftk-imager
- Autopsy: https://www.autopsy.com

## Evidence
- **HD-001**
	- Drive Model: JMicron Generic USB Device
	- Drive Serial Number: `0123456789ABCDEF`
	- Source Data Size: `476940 MB`
	- MD5 checksum: `808b681e557864a91568a4d6de42f2c9`
	- SHA-1 checksum: `093eeddb84cf7c73d63ffc83f06244f3d7a2c6b7`
- **TD-001**
	- Note: consegnata dall'attore

## Confronto tra USB e HD
> Sono stati trovati sull'HDD delle corrispondenze per i seguenti file:
> - `Solito.eml`: `/img_hdd.E01/vol_vol3/Documenti/Solito.eml`

- Mail:
	- File: `001_Richiesta informazioni sulle opzioni di spedizione.eml`
		- md5: `5a92b27e5faf5a160fb684f448fa3db0`
		- sha-1: `79dc4f547b2bb700923008cd185d864a7057cb30`
	- File: `002_Richiesta informazioni sulle opzioni di spedizione.eml`
		- md5: `344a404af229ab50edd4d3b29d0a117d`
		- sha-1: `8f446cb0a4fbdfa6b1dd4e886cafe18691675886`
	- File: `003_Solito.eml`
		- md5: `9e41acfa10d77d7f9cb77e405a3f1e97`
		- sha-1: `01135a5dc3840391d999df3ec57e5684ccd71a6d`
	- File: `004_Conferma della Proposta e Richiesta di Preventivi.eml`
		- md5: `b422bb342c3d5344c83c9ed7c05254ba`
		- sha-1: `340d621fcbc2d26c5b074592ce6e7bbc06f6fea9`
	- File: `005_Solito.eml`
		- md5: `108d202d6bda3e49627c368caaf9469e`
		- sha-1: `68c128cb922947dd4284911a74c9c0617132f904`
	- File: `006_Conferma della Proposta e Richiesta di Preventivi.eml`
		- md5: `85dadd2f3c585817f53042fa66970c4e`
		- sha-1: `b21ba90fa2d9e4ea30cf962f016c683e32943515`
	- File: `Quantitativo Totale di Merce per Spedizione-2.eml`
		- md5: `a2d4d833f3cd7d2fd73787bf3a25731c`
		- sha-1: `a203baa3b8087304f40f8573b1029c9d9b30371c`
	- File: `Quantitativo Totale di Merce per Spedizione-3.eml`
		- md5: `33c0e02a0319f7cddb6861df15247294`
		- sha-1: `6f733c9dfd6d540e92dfef7350befaa04160a4e6`
	- File: `Reclamo per Mancanza di Merce alla Consegna-2.eml`
		- md5: `1bff11fa796a4bfb5e52f0a3bac2d0b7`
		- sha-1: `4c48c1cec4bfb3f1c5460691889120b23e5cd3e7`
	- File: `Reclamo per Mancanza di Merce alla Consegna-3.eml`
		- md5: `404382378fd96ae3e59ecfa9f24c7ff3`
		- sha-1: `a0ce09126373d5c7a00c6871e722d120d50894d0`
	- File: `Reclamo per Mancanza di Merce alla Consegna.eml`
		- md5: `6de659d9fc09f9598022a33d44fa4e11`
		- sha-1: `381c8948459bda1f68fa4338e5c75fc784a926c8`
	- File: `Solito.eml`
		- md5: `b0ffd30aee8bcf8fd956ab570c9a944e`
		- sha-1: `f649698b295c1c1271690f8101e677174f259fce`
	- File: `_Quantitativo Totale di Merce per Spedizione.eml`
		- md5: `c04fcc662ab51933f9c11af9941e7887`
		- sha-1: `bb2d50b8b036bb381c5c82d076ecdd6ca825d438`
- Documenti
	- File: `Consegna.pdf`
		- md5: `144f73d42b4829be3019c40e782521a3`
		- sha-1: `cb2e0517055310f65cfdaf5f7358fbe815b6f099`
	- File: `Preventivo.docx`
		- md5: `c6209c7f120a50c82326f5cc3f5af74b`
		- sha-1: `aad5987eda5fce8bc521f391b28f57e32ebf6ce0`
## Findings
### Persone
- Andrea Zanatta (di seguito Zanatta)
	- **Azienda**: 23Bottles
	- **Email**: anrea.zanatta@TTBottles.com
	- **Telefono**: 347 321 4254
- Giulia Zingaro o Cinzia Zingaro
	- **Azienda**: Partolini
	- **Email**: giulia.zingaro@partolini.com
	- **Email**: cinzia.zingaro@partolini.com
- Sara Minto (potrebbe essere Cinzia Zingaro)
	- **Email**: sara.minto80@gmail.com
- Giuseppe Pavan (acronimo MR)
	- **Email**: giuseppe.pavan74@gmail.com
### Comunicazioni
- anrea.zanatta@TTBottles.com -> giulia.zingaro@partolini.com
	- Richiesta informazioni su ordini di spedizione
	- Reply:
		- Proposta di telefonata lavorativa
		- Notes:
			- Giulia si firma come Cinzia Zingaro
- sara.minto80@gmail.com -> giuseppe.pavan74@gmail.com
	- Stasera ci troviamo al solito posto
	- Note: Sara si firma come CZ (Cinzia Zingaro?)

### File Trovati
- Important Documents: `Laura\Desktop`