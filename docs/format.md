# Format

CSV形式で記述します。
ただし、次の規則に従います。

- 文字コードはUTF-8である。
- 区切り文字は`,`(カンマ)である。
- 改行文字は`\n`(LF)である。
- 最終行は空白行である。
- 最終行を除いて空白行を含まない。
- 可能な限り項目を`"`(ダブルクォーテーション)で囲わない。
- 一行目はヘッダである。

The databases are described in CSV format with the following rules:

- The character encoding is UTF-8.
- The delimiter is `,` (comma).
- The newline character is `\n` (LF).
- The final line is a blank line.
- Except for the final line, there are no blank lines.
- Whenever possible, items are not enclosed in `"` (double quotation marks).
- The first line is the header.
