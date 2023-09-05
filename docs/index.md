Blog von Christian Matyas

## Technischer Hintergrund
Diese Webseite vereint zwei Features von Github: Github Pages und GitHub Actions auf der Vorlage von [jobindjohn](https://github.com/jobindjohn) - Danke für die Vorlage und die ganze Arbeit.
Intern verwendet die GitHub Actions das Projekt https://www.mkdocs.org welches eine Ordnerstruktur aus Markdown Dateien zu einer Webseite umbaut. Genau so eine Ordnerstruktur ist aber auch die Grundlage von Obsidian, was es zu einer perfekten Kombination macht. Über die GithubActions wird ein Buildserver erstellt, der Mkdocs bereits mitbringt und das Ergebnis von MkDocs wird in einem speziellen Branch für Github pages zur Verfügung gestellt = der perfekte Git Flow.