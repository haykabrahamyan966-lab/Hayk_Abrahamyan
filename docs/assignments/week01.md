# 1. Սկզբունքներ, գործելակերպ և կայքի ստեղծում

Այս շաբաթ ես աշխատեցի իմ ավարտական նախագծի գաղափարը հստակեցնելու ուղղությամբ և սկսեցի փաստաթղթավորման գործընթացը։

## Research

Fab Academy-ն պաշտոնապես մեկնարկեց սեպտեմբերի 5-ին` սկիզբ դնելով իմ ուսումնառության և գործընթացի փաստաթղթավորման ուղուն: Ուսուցչիս` Fab Lab Armenia-ից Օնիկի ուղղորդմամբ ու աջակցությամբ, ես սկսեցի ուսումնասիրել Fab Academy-ի նախկին ուսանողների աշխատանքները և ծանոթանալ ծրագրի կայքին` հատուկ ուշադրություն դարձնելով «Ուսուցողական նյութեր» (Tutorials) բաժնին: 

Այդ ընթացքում ես առանձնացրի փաստաթղթավորման և տարբերակների կառավարման համար անհրաժեշտ հիմնական գործիքները, այդ թվում` Git-ը` բովանդակությունը կառավարելու և Fab Academy-ի պահոց (repository) վերբեռնելու համար, ինչպես նաև Visual Studio Code-ը` կոդի և Markdown ֆայլերի գրման, խմբագրման ու սպասարկման համար:

---

## 2. Կայքի ստեղծման և կարգավորման քայլաշար

### Քայլ 1․ Ռեպոզիտորիայի կլոնավորում և local միջավայր
* GitHub-ից իմ համակարգիչ քաշեցի `Hayk_Abrahamyan` ռեպոզիտորիան:
* Պրոյեկտի պապկան բացեցի VS Code ծրագրով:
* Git Bash տերմինալում կարգավորեցի իմ օգտանունն ու էլ․ հասցեն.
  * `git config --global user.name "Hayk Abrahamyan"`
  * `git config --global user.email "your-email@example.com"`
  <figure markdown>

  ![](․․/images/2.jpg)

  <figcaption style="font-size: 0.85em; color: #1e88e5; text-align: center;">
    Ահա GitHub-ի վերջնական տեսքը ներբեռնված ֆայլերով։
  </figcaption>
</figure>

### Քայլ 2․ Deployment-ի խնդրի լուծումը (GitHub Actions)
* Առաջին push-ից հետո GitHub Actions-ի build-ը ձախողվեց:
* **Պատճառը.** GitHub Actions-ին ֆայլեր գրելու թույլտվություն (write permissions) տրված չէր:
* **Լուծումը.** GitHub-ում անցա **Settings > Actions > General > Workflow permissions**, ընտրեցի **Read and write permissions**, պահպանեցի և re-run արեցի workflow-ն:

### Քայլ 3․ Կայքի կառուցվածքը (`mkdocs.yml`)
VS Code-ում բացեցի `mkdocs.yml` ֆայլը և ավելացրեցի `nav` բաժինը՝ կայքի մենյուն ստեղծելու համար․
* Home (`index.md`)
* About (`about/index.md`)
* Assignments (`assignments/week01.md`)
* Final Project (`projects/final-project.md`)

### Քայլ 4․ Էջերի խմբագրում, նկարներ և հղումներ
* Գլխավոր էջը խմբագրելու համար օգտագործեցի `docs/index.md` ֆայլը:
* Նկարները տեղադրեցի `docs/images/` պապկայում և կիրառեցի ճիշտ Markdown սինտաքս. `![Նկար](images/231.jpg)`
* Հղումները տեղադրեցի ճիշտ փակագծերով. `[Տեքստ](URL)`

### Քայլ 5․ Փոփոխությունների հրապարակում (Git Workflow)
VS Code-ում ֆայլերը պահպանելուց հետո (`Ctrl + S`), տերմինալում հերթով կատարում եմ 3 հրամանները.
1. `git add .`
2. `git commit -m "Updated site documentation"`
3. `git push`

---

## 3. Օգտակար հղումներ

* [Git-ի ներբեռնում Windows-ի համար](https://git-scm.com/install/windows) — սա անհրաժեշտ է վեբ կայքում արված փոփոխությունների պահպանման համար։
* [Visual Studio Code-ի ներբեռնում](https://code.visualstudio.com/download) — կոդի և Markdown ֆայլերի խմբագրման ծրագիր։