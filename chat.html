<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChatAnt</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #5b5959;
        }
        header {
            font-size: 24px;
            margin-bottom: 20px;
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        input[type="text"] {
            padding: 10px;
            width: 500px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        .results {
    width: 80%; /* Atur lebar kontainer relatif */
    max-width: 600px; /* Batasi lebar maksimum */
    overflow-x: auto; /* Tambahkan scroll horizontal jika diperlukan */
}
        .results div {
            padding: 10px;
            background-color: #fff;
            border: 1px solid #ddd;
            margin-bottom: 10px;
            border-radius: 4px;
        }
		
		.results pre {
    white-space: pre; /* Tampilkan teks sesuai format asli */
    overflow-x: auto; /* Tambahkan scroll horizontal jika diperlukan */
    background-color: #f8f3f3; /* Latar belakang untuk membedakan */
    padding: 10px;
    border-radius: 4px;
    border: 1px solid #ddd;
    max-width: 100%; /* Batasi lebar agar sesuai dengan kontainer */
}
    </style>
</head>
<body>
    <header>ChatAnt</header>
    <form id="searchForm">
        <input type="text" id="searchInput" placeholder="Message Chat...">
        <button type="submit">send</button>
    </form>
    <div class="results" id="results"></div>

    <script>
        const data = {
            "penerimaan": [
                "tbmaster_po",
                "tbmaster_pb",
                "tbmaster_btb"
            ],
            "logistik": [
                "tbmaster_logistik",
                "tbmaster_inventory"
			],
            "listing": [
                "tbtr_delivery_spi",
                "tbtr_dsp_spi"	
            ],
			"refund klik": [
                "log_push_refund",
				"payment_klikigr"
                	
            ],
            "klik": [
                "tbtr_obi_h",
                "tbtr_obi_d",
				"log_createawb",
                "tbtr_awb_ipp",
				"tbtr_serahterima_ipp",
                "log_serahterima_ipp",
				 "tbtr_packing_obi",
				 "tbtr_obi_status"
				
				
            ],

            "pkmt": [
                "tbmaster_kkpkm",
                "tbmaster_pkmplus",
				"tbtr_usulanpkm"
				
				
				
            ],
			
			"lock": [
                "lock_monitor",
                "tblog_laravel_ias"
				
				
				
				
            ],
			
            "query pkmt": [
                `(SELECT KODEIGR,
  Divisi,
  Departement,
  Kategori,
  PLU,
  PRD_DESKRIPSIPANJANG AS NamaProduk,
  PRD_kodetag          AS KODETAG,
  PRD_UNIT             AS UNIT,
  PRD_FRAC             AS FRAC,
  PKM,
  MPKM,
  PKMP_MPLUSI AS MPLUSI,
  PKMP_MPLUSO AS MPLUSO,
  PKMP_MPLUSK AS MPLUSK,
  PKMP_MPLUST AS MPLUST,
  PKMT,
  PKM_QTY1,
  PKM_QTY2,
  PKM_QTY3,
  PKM_QTYAVERAGE,
  PKM_MINORDER AS MINOR,
  pkm_mindisplay AS MINDIS,
  PKM_LEADTIME,
  HARI_SALES1,
  HARI_SALES2,
  HARI_SALES3,
  KOEF,
  Flag_Pareto,
  PKM_SAFETY_STOCK,
  SLV_SERVICELEVEL_QTY,
  AVGQTYSALES
FROM
  (SELECT pkm_kodeigr      AS KODEIGR,
    PKM_PRDCD              AS PLU,
    PKM_KODEDIVISI         AS Divisi,
    PKM_KODEDEPARTEMENT    AS Departement,
    PKM_KODEKATEGORIBARANG AS Kategori,
    PKM_PERIODEPROSES      AS PERIODE_PROSES_PKM,
    PKM_PERIODE1           AS Bulan1,
    PKM_PERIODE2           AS Bulan2,
    PKM_PERIODE3           AS Bulan3,
    PKM_QTY1,
    PKM_QTY2,
    PKM_QTY3,
    PKM_HARI1      AS Hari_sales1,
    PKM_HARI2      AS HARI_SALES2,
    PKM_HARI3      AS HARI_SALES3,
    PKM_FLAGPARETO AS Flag_Pareto,
    PKM_SAFETY_STOCK,
    PKM_PKMT      AS PKMT,
    pkm_mpkm      AS MPKM,
    PKM_PKM       AS PKM,
    PKM_KOEFISIEN AS KOEF,
    PKM_LEADTIME,
    SLV_SERVICELEVEL_QTY,
    PKMP_MPLUSI,
    PKMP_MPLUSO,
    PKMP_MPLUSK,
    PKMP_MPLUST,
    PKM_MINORDER,
    pkm_mindisplay,
    PKM_QTYAVERAGE
  FROM TBMASTER_KKPKM
  LEFT JOIN
    (SELECT pkmp_kodeigr,
      SLV_PERIODE,
      SLV_PRDCD,
      pkmp_prdcd,
      SLV_SERVICELEVEL_QTY,
      PKMP_MPLUSI,
      PKMP_MPLUSO,
      PKMP_MPLUSK,
      PKMP_MPLUST
    FROM tbmaster_pkmplus
    FULL JOIN
      (SELECT SLV_KODEIGR,
        SLV_PERIODE,
        SLV_PRDCD,
        SLV_SERVICELEVEL_QTY
      FROM TBTR_SERVICELEVEL
      WHERE SLV_PERIODE = '202410'
      )SLV
    ON pkmp_prdcd         = slv_prdcd
    )SLVPKMP on PKM_PRDCD        = PKMP_PRDCD
  WHERE PKM_PERIODEPROSES = '112024'
  )PKM
LEFT JOIN TBMASTER_PRODMAST
on PLU=PRD_PRDCD
LEFT JOIN (SELECT SLS_PRDCD,(SLS_QTY_08 + SLS_QTY_09 + SLS_QTY_10)/3
 AVGQTYSALES  FROM TBTR_SALESBULANAN)SLS
ON PLU = SLS_PRDCD)`
            ],
			
	"cek koreksi me": [
                `SELECT TRUNC(lpp_koreksi) AS lpp_koreksi,
  lpp_prdcd,
  prd_deskripsipanjang
from (
SELECT LPP_TGL1,
  LPP_TGL2,
  LPP_KODEDIVISI,
  LPP_KODEDEPARTEMEN,
  LPP_KATEGORIBRG,
  LPP_PRDCD,
  PRD_DESKRIPSIPANJANG,
  PRD_UNIT,
  PRD_FRAC,
  coalesce(PRD_KODETAG,' ')AS PRD_KODETAG,
  coalesce(LPP_RPHBEGBAL,0)    AS LPP_RPHBEGBAL,
  coalesce(LPP_RPHBELI,0)     AS LPP_RPHBELI,
  coalesce(LPP_RPHBONUS,0)      AS LPP_RPHBONUS,
  coalesce(LPP_RPHTRMCB,0)             AS LPP_RPHTRMCB,
  coalesce(LPP_RPHRETURSALES,0)      AS LPP_RPHRETURSALES,
  coalesce(LPP_RPHRAFAK,0)        AS LPP_RPHRAFAK,
  coalesce(LPP_RPHREPACK,0)          AS LPP_RPHREPACK,
  coalesce(LPP_RPHLAININ,0)     AS LPP_RPHLAININ,
  coalesce(LPP_RPHSALES,0)        AS LPP_RPHSALES,
  coalesce(LPP_RPHKIRIM,0)    AS LPP_RPHKIRIM,
  coalesce(LPP_RPHPREPACKING,0)    AS LPP_RPHPREPACKING,
  coalesce(LPP_RPHHILANG,0)    AS LPP_RPHHILANG,
  coalesce(LPP_RPHLAINOUT,0)        AS LPP_RPHLAINOUT,
  coalesce(LPP_RPHINTRANSIT,0)      AS LPP_RPHINTRANSIT,
  coalesce(LPP_RPHADJ,0)      AS LPP_RPHADJ,
  coalesce(LPP_RPH_SELISIH_SO,0)    AS LPP_RPH_SELISIH_SO,
  coalesce(LPP_RPHAKHIR,0)  AS LPP_RPHAKHIR,
  coalesce(LPP_RPHAKHIR,0) - ( coalesce(LPP_RPHBEGBAL,0) + coalesce(LPP_RPHBELI,0) 
  + coalesce(LPP_RPHBONUS,0) + coalesce(LPP_RPHTRMCB,0) + coalesce(LPP_RPHRETURSALES,0) 
  + coalesce(LPP_RPHRAFAK,0) + coalesce(LPP_RPHREPACK,0) + coalesce(LPP_RPHLAININ,0)
  - coalesce(LPP_RPHSALES,0) - coalesce(LPP_RPHKIRIM,0) - coalesce(LPP_RPHPREPACKING,0)
  - coalesce(LPP_RPHHILANG,0) - coalesce(LPP_RPHLAINOUT,0) + coalesce(LPP_RPHINTRANSIT,0) 
  + coalesce(LPP_RPHADJ,0) + coalesce(LPP_RPH_SELISIH_SO,0)+coalesce(LPP_RPH_SELISIH_SOIC,0)) AS LPP_KOREKSI
FROM TBTR_LPP,
  TBMASTER_PRODMAST
WHERE lpp_prdcd = prd_prdcd
AND lpp_kodeigr ='33') sub 
WHERE TO_CHAR(lpp_tgl1,'yyyy-mm')='2024-10'
ORDER BY ABS(LPP_KOREKSI) DESC`
            ]		
			
        };

       const form = document.getElementById('searchForm');
        const resultsContainer = document.getElementById('results');

        form.addEventListener('submit', function(event) {
            event.preventDefault();
            const query = document.getElementById('searchInput').value.toLowerCase();
            resultsContainer.innerHTML = '';

        
			
			const normalizedQuery = query.replace(/atau/g, '').trim();
const searchKey = Object.keys(data).find(key =>
    normalizedQuery.includes(key) || 
    (key === "penerimaan" && 
        (normalizedQuery.includes("penerimaan") || normalizedQuery.includes("pengeluaran") || normalizedQuery.includes("retur"))
    ) ||
    (key === "klik" && 
        (normalizedQuery.includes("klik") || normalizedQuery.includes("serah terima") || normalizedQuery.includes("ipp"))
    )
);
			
			 

            if (searchKey && data[searchKey]) {
                data[searchKey].forEach(item => {
                    const resultDiv = document.createElement('div');
                   if (searchKey === "query pkmt" || searchKey === "query cek koreksi me" || searchKey === "cek koreksi me") {
                        const pre = document.createElement('pre');
                        pre.textContent = item;
                        resultDiv.appendChild(pre);
                    } else {
                        resultDiv.textContent = item;
                    }
                    resultsContainer.appendChild(resultDiv);
                });
            } else {
                resultsContainer.innerHTML = '<div>Hasil tidak ditemukan</div>';
            }
        });
    </script>
</body>
</html>
