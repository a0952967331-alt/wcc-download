# 工作控制中心

Windows 本機工作控制中心免費試用版。

- 資料保存在自己的電腦
- 不需要帳號
- 專案 / 工作 / 里程碑
- 今天 / 近期 / 行事曆
- 跨專案掌握
- 備份 / 還原
- 封存 / 刪除復原

## 下載

[下載 工作控制中心 Windows 本機免費試用版（WorkControlCenter-Windows-Free-Trial.zip）](https://github.com/a0952967331-alt/wcc-download/releases/latest/download/WorkControlCenter-Windows-Free-Trial.zip)

這個連結永遠指向最新版本。

## 使用說明

解壓縮後閱讀 README.html，或直接執行 Work Control Center.exe。

## 更新

在程式內：設定 → 資料 → 更新程式，選擇下載好的 ZIP。程式會先在本機檢查官方簽章，不需要連網；檢查不通過就不會更新，資料不變。

如果舊版程式無法檢查新版的簽章，請從上方連結下載最新的 ZIP，依 README.html 的說明手動更新。

## 官方來源

只有從這個 GitHub 儲存庫下載的檔案才是官方發行版本。

每個版本都由本儲存庫的發行流程（`.github/workflows/sign-release.yml`）以 Sigstore 簽署，簽章檔放在 ZIP 內的 `Work-Control-Center/wcc-package.sigstore.json`。
