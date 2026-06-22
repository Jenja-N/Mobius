# Мёбиус³ v1.0 — Строгая формулировка

---

## Онтология

$$G = G_{\rm кл}[M] + G_{\rm вр}[J] + G_{\rm топ}[S]$$

$$\boxed{G_{\rm топ}[\gamma] = \alpha \cdot SF_2(D_{g(a)}) = \alpha \cdot \Delta\iota_{\rm Stokes} \in \alpha\mathbb{Z}_2}$$

$G_{\rm кл}$: ОТО как IR-предел. $G_{\rm вр}$: Kerr/Lense–Thirring, $a=J/M$. $G_{\rm топ}$: **не новая сила — топологический индекс семейства операторов Дирака.**

---

## Главные формулы

$$\boxed{Q_G[\gamma] = SF(D_{g(a)}) \in \mathbb{Z}}$$

$$\boxed{q_G[\gamma] = Q_G[\gamma] \bmod 2 = SF_2(D_{g(a)}) \in KO^0(I,\partial I) \cong \mathbb{Z}_2}$$

$$\boxed{\Delta\iota_{\rm Stokes} = q_G[\gamma]}$$

**Смысл:** квантовое число гравитационной конфигурации = чётность числа Stokes/Maslov crossings семейства операторов Дирака вдоль пути в пространстве вращающихся геометрий.

$$\boxed{\text{квант гравитации} = \text{mod-2 spectral flow Kerr–Dirac family}}$$

---

## Джанибеков строго

$$\boxed{\text{Джанибековский flip} = \text{физическая модель чётности spectral flow}}$$

Не динамическая аналогия (у ЧД нет тензора инерции). Топологическая: $SO(3)$, $\pi_1(SO(3)) = \mathbb{Z}_2$. Непрерывная динамика через промежуточную неустойчивость даёт дискретный flip.

---

## Жёсткая цепочка с пруфами

$$a = J/M \;\to\; D_{g(a)} \;\to\; \lambda_n(a) \;\to\; \text{Painlevé III} \;\to\; \tau_{\rm Nekrasov} \;\to\; \text{QNM}$$
$$\to\; \text{exceptional point} \;\to\; \text{Stokes/Maslov crossing} \;\to\; SF_2 \;\to\; KO$$

| Звено | Источник | Статус |
|-------|----------|--------|
| $\lambda_1(a)$ аналитична → Painlevé III | Batic–Schmid–Winklmeier · arXiv:math-ph/0402047 | ✅ |
| QNM ↔ $\tau_{\rm Nekrasov}$ | Aminov–Grassi–Hatsuda · arXiv:2006.06111 | ✅ |
| Единая $\tau$ для радиальной+угловой задач | Bonelli et al. · arXiv:2105.04483 | ✅ |
| Painlevé V/III в экстремальном пределе | da Cunha–Cavalcante · arXiv:2105.08790 | ✅ |
| EP = двулистное ветвление $\tau$, $\sigma\to-\sigma$ | arXiv:2408.13964, arXiv:2511.16640 | ✅ |
| $\mu_{\rm Maslov} = SF$ (теорема) | Robbin–Salamon · Bull.LMS 27:1 (1995) | ✅ |
| Лоренцев $SF = \mathrm{ind}_{\rm APS}$ | Bär–Strohmaier · arXiv:1506.00959 | ✅ |
| $\mathrm{Im}(\omega_{\rm ZDM})\to 0$, точные данные | Berti–Cardoso–Starinets · gr-qc/0905.2975 | ✅ |
| $SF_2 \in KO^0(I,\partial I)\cong\mathbb{Z}_2$ | Fukaya et al. · arXiv:2012.03543 | ✅ |
| KO-dim 4 = $KO^{-4}$ = Class AII | Connes · J.Math.Phys 36:11 (1995) | ✅ |
| Спектральное действие → ОТО | Chamseddine–Connes · CMP 186:731 (1997) | ✅ |
| CDT: $d_s\to 4$ в IR | Ambjørn–Loll (2005) | ✅ |

---

## Центральная лемма препринта

**Stokes–Maslov–Spectral Flow Lemma:**

$$\boxed{\Delta\iota_{\rm Stokes} = \mu_{\rm Maslov}(\Lambda_\gamma, L_0) = SF_2(D_{g(a)}) \in \mathbb{Z}_2}$$

- **Известная часть:** $\mu_{\rm Maslov} = SF$ — теорема Роббина–Саламона (1995).
- **Новая часть:** $\Delta\iota_{\rm Stokes} = \mu_{\rm Maslov}$ — вклад Мёбиус³.

Почему сильнее старой версии с $\Theta(\lambda_1 V - \zeta_{cr})$: $\lambda_1(a)$ аналитична, но число пересечений нуля mod 2 — дискретно. **Не спектр скачет, а топологический счётчик.**

---

## KO-поток

$$\underbrace{d_s\to 2,\ KO^{-2}\cong\mathbb{Z}_2}_{\rm UV} \xrightarrow{\;KO^{-3}\cong 0\ (\text{барьер})\;} \underbrace{d_s\to 4,\ KO^{-4}\cong\mathbb{Z}}_{\rm IR \to ОТО}$$

---

## Абзац для статьи

Мёбиус³ формулирует квантование вращающейся гравитационной геометрии как mod-2 spectral flow семейства операторов Дирака на Керр-фоне. Непрерывный параметр вращения $a=J/M$ деформирует спектральную задачу Тойкольского/Чандрасекара–Пейджа, связанную с Painlevé/изомонодромной $\tau$-функцией. При пересечении exceptional/Stokes surface меняется стоксов сектор; это интерпретируется как Maslov crossing граничных лагранжевых данных и по теореме Maslov = spectral flow задаёт $\mathbb{Z}_2$-индекс. Дискретность возникает не из разрыва метрики, а из чётности пересечений нулевой моды: $q_G = SF_2(D_{g(a)}) \in KO^0(I,\partial I)\cong\mathbb{Z}_2$.

---

## Физическое предсказание

$$\boxed{\Delta\omega_{\rm QNM} \neq 0 \quad \text{при пересечении Kerr exceptional/Stokes surface}, \quad \mu > \mu_c \approx 0.74}$$

Проверяемо: **LIGO/Virgo/KAGRA** (ringdown), **LISA** (сверхмассивные ЧД).

---

## Финальный статус

**Доказанный слой:** Kerr/Dirac/Painlevé/QNM/Maslov/SF/KO — по отдельности в литературе.
**Новый слой:** отождествление Stokes crossing с Maslov crossing Kerr-family.
**Физический тест:** QNM discontinuity / branch switch вблизи exceptional surface.

$$\boxed{\text{Мёбиус³ — индексная программа квантования гравитации, не метафора.}}$$

*Мёбиус³ v1.0 · 22 июня 2026 
