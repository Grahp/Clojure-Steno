Code:
```clojure
(defn lookup-str [s theory]
 (let [entry {:outline (outline/str->outline s)}]
  (lookup entry theory)))
```

Build:
```clojure
#TKEFPB    (defn  [])
HRUP       (defn lookup [])
ST-R       (defn lookup-str [])
WHR-S      (defn lookup-str [s])
*THAOERD   (defn lookup-str [s theory]
-PBG   - Logical line down and indent (like parinfer)
#HRET        (let []))
*ERPBTD      (let [entry]))
*UFPL        (let [entry {}]))
*BG          (let [entry {:}]))
+OUPBLT      (let [entry {:outline}]))
*FP          (let [entry {:outline ()}]))
+OUPBLT      (let [entry {:outline (outline)}]))
-RP          (let [entry {:outline (outline/)}]))
STAOR        (let [entry {:outline (outline/str)}]))
#O           (let [entry {:outline (outline/str->)}]))
+OUPBLT      (let [entry {:outline (outline/str->outline)}]
-PBG   - Line down and indent
#HRUP            (lookup)))
*ERPBTD          (lookup entry)))
*THAOERD         (lookup entry theory)))
```
