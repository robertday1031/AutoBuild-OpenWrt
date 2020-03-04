# AutoBuild-OpenWrt

Build OpenWrt firware [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) using GitHub Actions  
Hereby thank P3TERX for his amazing job: https://github.com/P3TERX/Actions-OpenWrt/

## Usage

- Sign up for [GitHub Actions](https://github.com/features/actions/signup)
- Fork [this GitHub repository](https://github.com/esirplayground/AutoBuild-OpenWrt)
- Click [.github/workflows] folder on the top of repo and you could see few workflow files, Each for one particular architecture(device).
- Edit the workflow file you desire，uncomment push section 3 lines together and submit the commit.(Other 2 methods wait you to discover)
- The build starts automatically. Progress can be viewed on the Actions page.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.

[For the details please visit my Y2B Channel (in Chinese) | 视频教程](https://www.youtube.com/c/esirplayground)
x86_64_lean_lede 給x86 64位元軟路由用 使用Lienol基於lean的源碼,綜合SSR+ & Passwall  https://github.com/Lienol/openwrt 分支: dev-lean-lede
Newifi3_lean_lede 給新Wifi3 D2 Mt7621架構無線路由器用
