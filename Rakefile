task :build do
    sh "bundle exec asciidoctor-pdf -a scripts=cjk -a pdf-theme=default-with-fallback-font docs/resume.adoc -D dist"
end

task :show do
    sh "open dist/resume.pdf"
end
