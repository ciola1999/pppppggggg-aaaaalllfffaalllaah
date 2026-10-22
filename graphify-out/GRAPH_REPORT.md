# Graph Report - web-public  (2026-10-22)

## Corpus Check
- 137 files · ~69,973 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 6 file(s) not represented in the graph (top: (none) 3, .example 1, .lock 1)

## Summary
- 847 nodes · 2206 edges · 26 communities (23 shown, 3 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 12 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `a546e216`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- getReadyPublicDatabase
- app/page.tsx
- landing-collections.ts
- cn
- services/pmb.ts
- license.ts
- wali-tagihan.ts
- pmb-pembayaran.ts
- ref_bun_test
- pmb-dapodik.ts
- berkas-sekolah.ts
- compilerOptions
- package.json
- biome.json
- FormPendaftaran
- siapkan-berkas.ts
- dependencies
- FormPendaftaran.tsx
- scripts
- sitemap.ts
- FormMasuk
- devDependencies
- engines
- AGENTS.md
- postcss.config.mjs

## God Nodes (most connected - your core abstractions)
1. `getReadyPublicDatabase()` - 51 edges
2. `next` - 41 edges
3. `cn()` - 35 edges
4. `react` - 31 edges
5. `@libsql/client` - 25 edges
6. `FormPendaftaran()` - 22 edges
7. `KataMuncul()` - 19 edges
8. `lucide-react` - 18 edges
9. `Button` - 18 edges
10. `Beranda()` - 17 edges

## Surprising Connections (you probably didn't know these)
- `GET()` --calls--> `getReadyPublicDatabase()`  [EXTRACTED]
  src/app/api/konten/berita/[slug]/gambar/route.ts → src/lib/server/db.ts
- `POST()` --calls--> `readGelombangAktif()`  [EXTRACTED]
  src/app/api/pmb/daftar/route.ts → src/lib/services/pmb.ts
- `POST()` --calls--> `readPilihanPmb()`  [EXTRACTED]
  src/app/api/pmb/daftar/route.ts → src/lib/services/pmb.ts
- `POST()` --calls--> `tulisPendaftaran()`  [EXTRACTED]
  src/app/api/pmb/daftar/route.ts → src/lib/services/pmb.ts
- `POST()` --calls--> `tolakPilihanPmb()`  [EXTRACTED]
  src/app/api/pmb/daftar/route.ts → src/lib/validations/pmb.ts

## Import Cycles
- None detected.

## Communities (26 total, 3 thin omitted)

### Community 0 - "getReadyPublicDatabase"
Cohesion: 0.05
Nodes (93): buildDateWib, nextConfig, next, server-only, GET(), runtime, jawabKegagalan(), POST() (+85 more)

### Community 1 - "app/page.tsx"
Cohesion: 0.05
Nodes (70): GET(), runtime, HalamanBerita(), metadata, generateMetadata(), HalamanDetailBerita(), Props, HalamanKontak() (+62 more)

### Community 2 - "landing-collections.ts"
Cohesion: 0.07
Nodes (69): react, BagianTeks(), HalamanProgram(), KepalaBagian(), metadata, FacilitiesSection(), FacilitiesSectionProps, IKON_FASILITAS (+61 more)

### Community 3 - "cn"
Cohesion: 0.07
Nodes (49): lucide-react, FaqSection(), FaqSectionProps, IKON_TAHAPAN, PmbOverviewSection(), SambutanVisiSectionProps, PESAN_WA_PMB, StickyAction() (+41 more)

### Community 4 - "services/pmb.ts"
Cohesion: 0.06
Nodes (44): @libsql/client, zod, client, config, assertOperatorContact(), isValidOperatorEmail(), isValidOperatorPhone(), maskEmail() (+36 more)

### Community 5 - "license.ts"
Cohesion: 0.06
Nodes (46): LicenseKind, LicensePayload, LicenseReadOnlyReason, LicenseState, LicenseStatus, HALAMAN_TIDAK_TERSEDIA, PESAN_PENDAFTARAN_DITUTUP, PESAN_SITUS_TIDAK_TERSEDIA (+38 more)

### Community 6 - "wali-tagihan.ts"
Cohesion: 0.08
Nodes (39): HalamanKehadiran(), MENU, metadata, revalidate, WaliLayout(), HalamanNilai(), PesanGagal(), HalamanPresensiMapel() (+31 more)

### Community 7 - "pmb-pembayaran.ts"
Cohesion: 0.06
Nodes (34): RFC-6238, collectTests(), runTest(), tests, worker(), workers, desktopSrc, filesToCopy (+26 more)

### Community 8 - "ref_bun_test"
Cohesion: 0.08
Nodes (23): RFC-1918, DATABASE_NOT_CONFIGURED_MESSAGE, databaseConfigIssue(), FILE_DATABASE_BUSY_TIMEOUT_MS, fileDatabaseOptions(), isTruthyFlag(), resolveServerDatabaseConfig(), ServerDatabaseConfig (+15 more)

### Community 9 - "pmb-dapodik.ts"
Cohesion: 0.10
Nodes (31): ALAT_TRANSPORTASI, angka(), barisEksporDapodik(), DataDapodik, dataDapodikDasarSchema, dataDapodikSchema, digit(), hpLokal() (+23 more)

### Community 10 - "berkas-sekolah.ts"
Cohesion: 0.16
Nodes (19): berkasSekolahSchema, JENIS_BERKAS_SEKOLAH, MAKS_BASE64_BERKAS, MAKS_BYTE_BERKAS, MIME_BERKAS_SEKOLAH, PESAN_BERKAS_TERLALU_BESAR, PESAN_PENDAFTAR_SUDAH_SISWA, SQL_BUANG_BERKAS_PMB_TERPINDAH (+11 more)

### Community 11 - "compilerOptions"
Cohesion: 0.11
Nodes (18): compilerOptions, allowJs, esModuleInterop, incremental, isolatedModules, jsx, lib, module (+10 more)

### Community 12 - "package.json"
Cohesion: 0.11
Nodes (17): name, packageManager, private, version, @biomejs/biome, clsx, embla-carousel-react, postcss (+9 more)

### Community 13 - "biome.json"
Cohesion: 0.12
Nodes (15): source, assist, actions, css, parser, next, react, extends (+7 more)

### Community 14 - "FormPendaftaran"
Cohesion: 0.23
Nodes (16): FormPendaftaran(), bagianLangkah(), isianGalat(), kirim(), langkahSah(), lanjut(), perbaruiPenentu(), pindah() (+8 more)

### Community 15 - "siapkan-berkas.ts"
Cohesion: 0.17
Nodes (13): pilihBerkas(), OptimizedImageResult, optimizeImageDataUrl(), optimizeImageFile(), OptimizeImageOptions, bacaDataUrl(), HasilSiapkanBerkas, isiBase64() (+5 more)

### Community 16 - "dependencies"
Cohesion: 0.14
Nodes (14): dependencies, clsx, embla-carousel-react, @libsql/client, lucide-react, next, postcss, react (+6 more)

### Community 17 - "FormPendaftaran.tsx"
Cohesion: 0.15
Nodes (9): Kiriman, LANGKAH, BerkasSekolah, JenisBerkasSekolah, LABEL_JENIS_BERKAS, AGAMA, JENJANG_PENDIDIKAN, KEBUTUHAN_KHUSUS (+1 more)

### Community 18 - "scripts"
Cohesion: 0.17
Nodes (12): scripts, build, cek:skema, check, check:quick, dev, format, lint (+4 more)

### Community 19 - "sitemap.ts"
Cohesion: 0.26
Nodes (8): dynamic, robots(), dynamic, sitemap(), NAVIGASI, normalkan(), resolveSiteUrl(), SiteUrlEnvironment

### Community 20 - "FormMasuk"
Cohesion: 0.24
Nodes (4): FormMasuk(), Langkah, ModeMasuk, HalamanMasukWali()

### Community 21 - "devDependencies"
Cohesion: 0.29
Nodes (7): devDependencies, @biomejs/biome, @types/bun, @types/node, @types/react, @types/react-dom, typescript

### Community 22 - "engines"
Cohesion: 0.67
Nodes (3): engines, bun, node

## Knowledge Gaps
- **12 isolated node(s):** `../biome.json`, `@tailwindcss/postcss`, `postcss`, `tailwindcss`, `@biomejs/biome` (+7 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 282 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `next` connect `getReadyPublicDatabase` to `app/page.tsx`, `landing-collections.ts`, `cn`, `license.ts`, `wali-tagihan.ts`, `pmb-pembayaran.ts`, `ref_bun_test`, `package.json`, `FormPendaftaran.tsx`, `sitemap.ts`, `FormMasuk`?**
  _High betweenness centrality (0.198) - this node is a cross-community bridge._
- **What connects `../biome.json`, `@tailwindcss/postcss`, `postcss` to the rest of the system?**
  _12 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `getReadyPublicDatabase` be split into smaller, more focused modules?**
  _Cohesion score 0.052112488337998135 - nodes in this community are weakly interconnected._
- **Why does `@libsql/client` connect `services/pmb.ts` to `getReadyPublicDatabase`, `app/page.tsx`, `landing-collections.ts`, `license.ts`, `wali-tagihan.ts`, `package.json`?**
  _High betweenness centrality (0.135) - this node is a cross-community bridge._
- **Should `app/page.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.053479381443298966 - nodes in this community are weakly interconnected._
- **Why does `react` connect `landing-collections.ts` to `getReadyPublicDatabase`, `app/page.tsx`, `cn`, `wali-tagihan.ts`, `pmb-pembayaran.ts`, `package.json`, `FormPendaftaran.tsx`, `FormMasuk`?**
  _High betweenness centrality (0.107) - this node is a cross-community bridge._
- **Should `landing-collections.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.0699942627653471 - nodes in this community are weakly interconnected._