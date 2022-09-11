# optbv-spec
optbv specifications, translated for friends from [@gsi-cyberjapan/optimal_bvmap](https://github.com/gsi-cyberjapan/optimal_bvmap).

# README.md
<dl>
<dt>template url</dt>
<dd>https://maps.gsi.go.jp/xyz/experimental_bvmap-v1/{z}/{x}/{y}.pbf</dd>
<dt>default style.json</dt>
<dd>https://gsi-cyberjapan.github.io/optimal_bvmap/style/std.json</dd>
<dt>skeleton style.json</dt>
<dd>https://gsi-cyberjapan.github.io/optimal_bvmap/style/skeleton.json</dd>
<dt>minzoom</dt>
<dd>4</dd>
<dt>maxzoom</dt>
<dd>16</dd>
<dt>release data</dt>
<dd>2022-09-06</dd>
<dt>demo (Mapbox GL JS 1.13.0)</dt>
<dd>https://gsi-cyberjapan.github.io/optimal_bvmap</dd>
<dt>license</dt>
<dd>[compatible with CC-BY 4.0 international](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)</dd>
</dl>

# feature codes

# list of source layers
## AdmArea
<dl>
<dt>meaning</dt><dd>administrative area</dd>
<dt>ja</dt><dd>行政区画</dd>
</dl>

## AdmBdry
<dl>
<dt>meaning</dt><dd>administrative boundary</dd>
<dt>ja</dt><dd>行政区画界線</dd>
</dl>

## RdEdg
<dl>
<dt>meaning</dt><dd>road edge</dd>
<dt>ja</dt><dd>道路縁</dd>
</dl>

## RdCompt
<dl>
<dt>meaning</dt><dd>road component</dd>
<dt>ja</dt><dd>道路構成線</dd>
</dl>

## RdCL
<dl>
<dt>meaning</dt><dd>road centerline</dd>
<dt>ja</dt><dd></dd>
</dl>

## RailTrCL
<dl>
<dt>meaning</dt><dd>railroad track centerline</dd>
<dt>ja</dt><dd>軌道の中心線</dd>
</dl>

## BldA
<dl>
<dt>meaning</dt><dd>building area</dd>
<dt>ja</dt><dd>建築物</dd>
</dl>

## BldL
<dl>
<dt>meaning</dt><dd>building outline<dd>
<dt>ja</dt><dd>建築物の外周線</dd>
</dl>

## StrctLine
<dl>
<dt>meaning</dt><dd>structural line</dd>
<dt>ja</dt><dd>構造物線</dd>
</dl>

## StrctArea
<dl>
<dt>meaning</dt><dd>structural area</dd>
<dt>ja</dt><dd>構造物面</dd>
</dl>

## WA
<dl>
<dt>meaning</dt><dd>water area</dd>
<dt>ja</dt><dd>水域</dd>
</dl>

## Cstline
<dl>
<dt>meaning</dt><dd>coastline</dd>
<dt>ja</dt><dd>海岸線</dd>
</dl>

## WL
<dl>
<dt>meaning</dt><dd>water line</dd>
<dt>ja</dt><dd>水涯線</dd>
</dl>

## RvrCL
<dl>
<dt>meaning</dt><dd>river centerline</dd>
<dt>ja</dt><dd>河川中心線</dd>
</dl>

## WStrL
<dl>
<dt>meaning</dt><dd>waterside structure line</dd>
<dt>ja</dt><dd>水部構造物線</dd>
</dl>

## WRltLine
<dl>
<dt>meaning</dt><dd>water related line</dd>
<dt>ja</dt><dd>水部表記線</dd>
</dl>

## SpcfArea
<dl>
<dt>meaning</dt><dd>specific area</dd>
<dt>ja</dt><dd>特定地区界</dd>
</dl>

## Cntr
<dl>
<dt>meaning</dt><dd>contour</dd>
<dt>ja</dt><dd>等高線</dd>
</dl>

## Isbt
<dl>
<dt>meaning</dt><dd>isobath</dd>
<dt>ja</dt><dd>等深線</dd>
</dl>

## TpgphArea
<dl>
<dt>meaning</dt><dd>topographical representative area</dd>
<dt>ja</dt><dd>地形表記面</dd>
</dl>

## TpgphLine
<dl>
<dt>meaning</dt><dd>topographical representative line</dd>
<dt>ja</dt><dd>地形表記線</dd>
</dl>

## RailCL
<dl>
<dt>meaning</dt><dd>railroad centerline</dd>
<dt>ja</dt><dd>鉄道中心線</dd>
</dl>

## PwrTrnsmL
<dl>
<dt>meaning</dt><dd>power transmission line</dd>
<dt>ja</dt><dd>送電線</dd>
</dl>

## Anno
<dl>
<dt>meaning</dt><dd>annotation</dd>
<dt>ja</dt><dd>注記</dd>
</dl>

# attribute specifications

# Information source
[電子国土基本図 地図情報 ファイル仕様書 第1.1版](https://www.gsi.go.jp/common/000189294.pdf)
