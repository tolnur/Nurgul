 - имя: Build Docs
        использование: ./.github/actions/build-docs
 - имя: опубликовать документы на gh-страницах
        использование: maxheld83/ghpages@v0.2.1
        использование: maxheld83/ghpages@v0.3.0
        env:
          BUILD_DIR: документы/
          GH_PAT: ${{ секреты.GH_PAT }}
