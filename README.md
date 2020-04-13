# gist-collection-bayes
> Gistで公開したベイズ関連の実装例まとめ

1. WAIC&WBIC with pystan2.ipynb
   - PyStanによるWAICとWBICの計算例
   - https://gist.github.com/narrowlyapplicable/bf6110beaca11934d47838dfbe2d19f1
     - WAIC(Widely Applicable Information Criterion)
     - WBIC(Widely-Applicable Bayesian Information Criterion)
2. structural-changes-withCRP.ipynb
   - 中華料理店過程（Chinese Restaurant Process）による構造変化推定
     - 佐藤一誠先生のMLPノンパラベイズ本にある事例（実装なし）をPython実装したもの
   - https://gist.github.com/narrowlyapplicable/0922b733fa2cc75167f71eff448bf1a4
3. GPy_note.ipynb
   - ガウス過程用ライブラリGPyのTips
   - https://gist.github.com/narrowlyapplicable/98d12825d0a1c422da500c758b93fd95
     - hyperparametersに対するPrior設定法
     - hyperparametersをMCMCで推定する方法
     - GPyのplot紹介（一部）
4. GP&TPonSinWave.ipynb
   - sin波に対してガウス過程とその変種であるStudent-t過程を試行したもの。
     - 末尾にGPyによるMCMC利用法を記載。
   - https://gist.github.com/narrowlyapplicable/79e10c4e26e447f3e137939aba468c21
5. ts-test
   - RStanによる時系列データに対する検定<http://statmodeling.hatenablog.com/entry/difference-between-time-courses>をPyStanで試しただけ。
     - PyStan入門時に描いたものなので、色々大目に見て下さい。 
