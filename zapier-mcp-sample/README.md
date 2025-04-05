# Dify と Zapier MCP を連携するサンプル

## MCP とは

**MCP（Model Context Protocol）** とは、**AI アシスタント**と**外部データソース**や**ツール**を標準化された方法で接続するための通信規格です。

MCP は、**​Anthropic 社**によって **2024 年 11 月**に発表されました。​Anthropic 社は、Model Context Protocol（MCP）を「AI アプリケーションにおける USB-C ポートのようなもの」と説明しています。

## Dify と Zapier を接続する手順

1. Zapier でアカウントを作成する
2. Zapier で MCP Server の URL を生成する
3. AI Action の内容を編集する
4. AI Action が定義できたら Dify を立ち上げて接続させる
5. 最初から作成で、チャットフローを選択
6. LLM ブロックを削除してエージェントブロックを追加
7. 回答ブロックとエージェントブロックを接続させる
8. Dify マーケットプレイスから MCP SSE プラグインをインストールする
9. zapier mcp server の URL を環境変数として追加

## 参考文献

- [Dify MCP Plugin Hands-On Guide: Integrating Zapier for Effortless Agent Tool Calls](https://dify.ai/blog/dify-mcp-plugin-hands-on-guide-integrating-zapier-for-effortless-agent-tool-calls)
- [Dify と Zapier MCP を連携する方法を解説！](https://note.com/kazu_t/n/na0065addc7fb)
- [Zapier 公式サイト](https://zapier.com/)
- [MCP Quickstart For Server Developers](https://modelcontextprotocol.io/quickstart/server#why-claude-for-desktop-and-not-claude-ai)
- [MCP Quickstart For Client Developers](https://modelcontextprotocol.io/quickstart/client)
- [Zapier get started](https://actions.zapier.com/)
