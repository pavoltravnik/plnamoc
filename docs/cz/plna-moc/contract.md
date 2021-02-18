<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script>function getval(sel){
	if (sel.value === "1") {
		ucel.textContent = "ve věci vydání všech matričních dokladů, zejména rodného listu, oddacího listu, úmrtního listu, dokladu o registrovaném partnerství), nahlédnutí do matriční knihy, k získaní výpisu z ní v přítomnosti matrikáře (plná moc musí být úředně ověřena podle § 25 odst. 8 zákona č. 301/2000 Sb. o matrikách, jménu a příjmení)"
	} else if (sel.value === "2") {
		ucel.textContent = "ve věci vydání výpisu Rejstříku trestů České republiky, k podání žádosti/í a převzetí 1 ks výpisu/ů z rejstříku trestů."
	} else if (sel.value === "3") {
		ucel.textContent = "ve věci vydání výpisu Rejstříku trestů České republiky, přičemž výpis Rejstříku trestů má obsahovat informace z evidence rejstříku trestů jiného členského státu Evropské unie, ve kterém zmocnitel měl nebo má bydliště nebo jehož byl státním příslušníkem."
	} else if (sel.value === "4") {
		ucel.textContent = "ve věci získaní potvrzení o dosaženém vzdělání a to včetně kopie diplomu na škole nebo univerzitě, na které zmocnitel studoval."
	} else {
		ucel.textContent = ""
	}
}
</script>
<style>@media print
{    
    .no-print, .no-print *
    {
        display: none !important;
    }
}</style>


# PLNÁ MOC

Zmocnitelem je fyzická osoba

<input type="text" size="40" placeholder="Jméno a příjmení"/> 
rozený/á <input type="text" size="20" placeholder="Rodné příjmení"/>

Občanství <input type="text" size="20" placeholder="občanství"/> 
typ dokladu <input type="text" size="5" placeholder="typ"/> 
číslo dokladu <input type="text" size="10" placeholder="číslo"/>

Narozený: <input type="text" size="15" placeholder="Datum narození"/>

Rodné číslo: <input type="text" size="15" placeholder="Rodné číslo"/>

Bydliště: <input type="text" size="40" placeholder="Adresa"/>

<input type="text" size="40" placeholder="Město a PSČ"/>

(dále jako „**Zmocnitel**“)

Zmocněncem je fyzická osoba


<input type="text" size="40" placeholder="Jméno a příjmení"/>

Narozený: <input type="text" size="15" placeholder="Datum narození"/>

Rodné číslo: <input type="text" size="15" placeholder="Rodné číslo"/>

Bydliště: <input type="text" size="40" placeholder="Adresa"/>

<input type="text" size="40" placeholder="Město a PSČ"/>

(dále jako „**Zmocněnec**“)

Zmocnitel tímto zmocňuje Zmocněnece, k tomu, aby ho zastupoval:

<select class="no-print" onchange="getval(this);">
  <option selected>vyber</option>
  <option value="1">Matriční doklady</option>
  <option value="2">Výpis z RT</option>
  <option value="3">Výpis z RT zahraničí</option>
  <option value="3">Diplom</option>
</select>

<ul>
  <li id="ucel"></li>
</ul>


Tato plná moc se uděluje na dobu určitou, a to do <input type="text" size="15" placeholder="dátum"/>.

Tato plná moc zaniká také doručením oznámení o odvolání této plné moci Zmocněnci.

Zmocněnec má právo vykonávat všechny právní a/nebo faktické úkony spojené s předmětem této plné moci.

Zmocněnec má zejména právo podávat žádosti, nahlížet do spisu, přebírat doručované písemnosti, pořebírat potvrzení a rozhodnutí, podávat odvolání, stížnosti a také další opravné prostředky.



V <input type="text" size="40" placeholder="mesto"/>,
dne <input type="text" size="15" placeholder="dátum"/>.

<br/><br/><input type="text" size="40" placeholder="Meno a priezvisko"/>

Zmocnitel




Tuto plnou moc v plném rozsahu přijímám.


V <input type="text" size="40" placeholder="mesto"/>,
dne <input type="text" size="15" placeholder="dátum"/>.

<br/><br/><input type="text" size="40" placeholder="Meno a priezvisko"/>

Zmocněnec

