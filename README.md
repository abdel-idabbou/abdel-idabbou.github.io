import React from "react";

export default function Portfolio() {
  return (
    <div className="min-h-screen bg-slate-950 text-slate-50 flex justify-center px-4 py-10">
      <main className="w-full max-w-5xl grid gap-10 md:grid-cols-[1.1fr_1.6fr]">
        {/* Left column: profile */}
        <section className="bg-slate-900/70 border border-slate-800 rounded-3xl p-6 md:p-8 flex flex-col gap-8 shadow-xl">
          {/* Avatar + name */}
          <div className="flex flex-col items-center text-center gap-4">
            <div className="w-40 h-40 rounded-3xl overflow-hidden border border-slate-700 bg-slate-800/80">
              {/* Replace this with your real image <img src="/mein-foto.jpg" alt="Abdelghafour" className="w-full h-full object-cover" /> */}
              <div className="w-full h-full flex items-center justify-center text-sm text-slate-400">
                Foto einfügen
              </div>
            </div>
            <div>
              <p className="text-xs tracking-[0.35em] uppercase text-slate-400 mb-1">
                HTWK Student
              </p>
              <h1 className="text-3xl font-semibold tracking-tight">Abdelghafour</h1>
              <p className="text-sm text-slate-400 mt-1">
                Wirtschaftsingenieurwesen Maschinenbau (B.Eng)
              </p>
            </div>
          </div>

          {/* Kontakt */}
          <div className="space-y-3">
            <h2 className="text-sm font-semibold tracking-[0.25em] text-slate-400 uppercase">
              Kontakt
            </h2>
            <div className="space-y-1 text-sm">
              <p className="flex items-center gap-2">
                <span className="inline-flex h-7 w-7 items-center justify-center rounded-full border border-slate-700 text-xs">
                  📞
                </span>
                <a href="tel:+4917628903304" className="hover:text-sky-400 transition-colors">
                  +49 176 2890 3304
                </a>
              </p>
              <p className="flex items-center gap-2">
                <span className="inline-flex h-7 w-7 items-center justify-center rounded-full border border-slate-700 text-xs">
                  ✉️
                </span>
                <a
                  href="mailto:abdelghafour.kacm.1@gmail.com"
                  className="hover:text-sky-400 transition-colors break-all"
                >
                  abdelghafour.kacm.1@gmail.com
                </a>
              </p>
              <p className="flex items-center gap-2">
                <span className="inline-flex h-7 w-7 items-center justify-center rounded-full border border-slate-700 text-xs">
                  📍
                </span>
                <span>Leipzig · 04299 · Deutschland</span>
              </p>
            </div>
          </div>

          {/* Sprachen */}
          <div className="space-y-3">
            <h2 className="text-sm font-semibold tracking-[0.25em] text-slate-400 uppercase">
              Sprachen
            </h2>
            <ul className="space-y-2 text-sm">
              <li className="flex items-center justify-between gap-4">
                <span>Arabisch</span>
                <span className="text-xs px-2 py-0.5 rounded-full bg-emerald-500/10 text-emerald-300 border border-emerald-500/30">
                  Muttersprache
                </span>
              </li>
              <li className="flex items-center justify-between gap-4">
                <span>Deutsch</span>
                <span className="text-xs px-2 py-0.5 rounded-full bg-sky-500/10 text-sky-300 border border-sky-500/30">
                  C1
                </span>
              </li>
              <li className="flex items-center justify-between gap-4">
                <span>Englisch</span>
                <span className="text-xs px-2 py-0.5 rounded-full bg-violet-500/10 text-violet-300 border border-violet-500/30">
                  B1
                </span>
              </li>
            </ul>
          </div>

          {/* Kurzprofil */}
          <div className="space-y-3 mt-auto">
            <h2 className="text-sm font-semibold tracking-[0.25em] text-slate-400 uppercase">
              Über mich
            </h2>
            <p className="text-sm text-slate-300 leading-relaxed">
              Ich bin angehender Wirtschaftsingenieur im Bereich Maschinenbau an der HTWK
              Leipzig mit einem starken technischen Hintergrund und Erfahrung in der
              Gastronomie. Struktur, Verantwortung und der direkte Kontakt mit Menschen
              sind mir wichtig – egal ob im Service, bei Veranstaltungen oder im
              Studium.
            </p>
          </div>
        </section>

        {/* Right column: content */}
        <section className="flex flex-col gap-8">
          {/* Hero / Intro */}
          <section className="bg-gradient-to-br from-slate-900/80 via-slate-900 to-slate-900/60 border border-slate-800 rounded-3xl p-6 md:p-8 shadow-xl">
            <p className="text-xs tracking-[0.35em] uppercase text-slate-400 mb-3">
              Portfolio
            </p>
            <h2 className="text-2xl md:text-3xl font-semibold tracking-tight mb-3">
              Wirtschaftsingenieurwesen & Serviceerfahrung
            </h2>
            <p className="text-sm md:text-base text-slate-300 max-w-2xl leading-relaxed">
              Zwischen Technik, Wirtschaft und Praxis: Ich verbinde mein Studium im
              Wirtschaftsingenieurwesen Maschinenbau mit echter Erfahrung im
              Gastronomie- und Eventbereich. Ich arbeite strukturiert, lerne schnell
              und übernehme gerne Verantwortung – im Team und eigenständig.
            </p>
          </section>

          {/* Ausbildung */}
          <section className="bg-slate-900/70 border border-slate-800 rounded-3xl p-6 md:p-8 space-y-5">
            <div className="flex items-center justify-between gap-4">
              <h2 className="text-lg md:text-xl font-semibold tracking-tight">
                Ausbildung
              </h2>
              <span className="text-xs px-3 py-1 rounded-full border border-slate-700 text-slate-300">
                Fokus: Technik & Sprache
              </span>
            </div>

            <div className="space-y-4 text-sm md:text-[0.93rem]">
              <div className="border-l border-slate-700 pl-4">
                <p className="text-xs uppercase tracking-[0.18em] text-slate-400">
                  ab Okt. 2025 · Leipzig
                </p>
                <p className="font-semibold">HTWK Leipzig</p>
                <p className="text-slate-300">Bachelor Wirtschaftsingenieurwesen Maschinenbau (B.Eng)</p>
              </div>

              <div className="border-l border-slate-700 pl-4">
                <p className="text-xs uppercase tracking-[0.18em] text-slate-400">
                  2024 – Juni 2025 · Lübeck
                </p>
                <p className="font-semibold">Technische Hochschule Lübeck</p>
                <p className="text-slate-300">Studienkolleg (FSP–C1), Schwerpunkt technische & ingenieurwissenschaftliche Fächer</p>
              </div>

              <div className="border-l border-slate-700 pl-4">
                <p className="text-xs uppercase tracking-[0.18em] text-slate-400">
                  2022 – 2025
                </p>
                <p className="font-semibold">Deutschkurs A1–C1</p>
                <p className="text-slate-300">Abschluss: B2-Zertifikat (Sprachzentrum)</p>
              </div>

              <div className="border-l border-slate-700 pl-4">
                <p className="text-xs uppercase tracking-[0.18em] text-slate-400">
                  2010 – 2022 · Marrakesch
                </p>
                <p className="font-semibold">El Housna · Grundschule, Realschule, Gymnasium</p>
                <p className="text-slate-300">Abitur · Note 2,4</p>
              </div>
            </div>
          </section>

          {/* Berufserfahrung */}
          <section className="bg-slate-900/70 border border-slate-800 rounded-3xl p-6 md:p-8 space-y-5">
            <div className="flex items-center justify-between gap-4">
              <h2 className="text-lg md:text-xl font-semibold tracking-tight">
                Berufserfahrung
              </h2>
              <span className="text-xs px-3 py-1 rounded-full border border-slate-700 text-slate-300">
                Gastronomie & Events
              </span>
            </div>

            <div className="space-y-4 text-sm md:text-[0.93rem]">
              <article className="border-l border-slate-700 pl-4">
                <p className="text-xs uppercase tracking-[0.18em] text-slate-400">
                  06/2025 – 09/2025 · Scharbeutz (Ostsee)
                </p>
                <p className="font-semibold">Grande Beach Café · Stationskellner</p>
                <ul className="mt-1 space-y-1 text-slate-300 list-disc list-inside">
                  <li>Selbstständige Betreuung einer Station im Tages- und Abendgeschäft</li>
                  <li>Aufnahme & Abwicklung von Bestellungen mit dem Kassensystem Orderman</li>
                  <li>Sicherstellung eines reibungslosen Serviceablaufs</li>
                  <li>Enge Zusammenarbeit mit Bar- und Küchenteam für Speisen & Getränke</li>
                </ul>
              </article>

              <article className="border-l border-slate-700 pl-4">
                <p className="text-xs uppercase tracking-[0.18em] text-slate-400">
                  09/2024 – 08/2025
                </p>
                <p className="font-semibold">Buhl Personal GmbH · Eventservicekraft</p>
                <ul className="mt-1 space-y-1 text-slate-300 list-disc list-inside">
                  <li>Gästeservice bei Veranstaltungen & Events</li>
                  <li>Unterstützung beim Auf- und Abbau</li>
                  <li>Kassiertätigkeiten & zuverlässiger Umgang mit Bargeld/Zahlungen</li>
                </ul>
              </article>
            </div>
          </section>

          {/* Call to action */}
          <section className="bg-gradient-to-r from-sky-600/80 to-violet-600/80 border border-slate-800 rounded-3xl p-6 md:p-8 flex flex-col md:flex-row items-start md:items-center justify-between gap-4 text-slate-50">
            <div>
              <h2 className="text-lg md:text-xl font-semibold tracking-tight mb-1">
                Lass uns zusammenarbeiten
              </h2>
              <p className="text-sm md:text-[0.95rem] text-slate-100/90 max-w-xl">
                Ob Nebenjob, Werkstudierendentätigkeit oder Projekt – ich freue mich über
                Anfragen rund um Technik, Organisation, Gastronomie oder Veranstaltungen.
              </p>
            </div>
            <div className="flex flex-wrap gap-3">
              <a
                href="mailto:abdelghafour.kacm.1@gmail.com"
                className="px-4 py-2 rounded-full bg-slate-950/10 border border-slate-100/60 text-sm font-medium hover:bg-slate-950/25 transition-colors"
              >
                E-Mail schreiben
              </a>
              <a
                href="tel:+4917628903304"
                className="px-4 py-2 rounded-full bg-slate-950/10 border border-slate-100/60 text-sm font-medium hover:bg-slate-950/25 transition-colors"
              >
                Anrufen
              </a>
            </div>
          </section>
        </section>
      </main>
    </div>
  );
}
