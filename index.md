      - name: Set environment variables
        run: |
          echo "FILE=index.md" >> $GITHUB_ENV
          echo "SEARCH='(?<!#)#{1,6}([\ \\t](.*))?$'" >> $GITHUB_ENV

