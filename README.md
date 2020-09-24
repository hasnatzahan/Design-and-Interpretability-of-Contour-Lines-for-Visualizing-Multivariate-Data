# Design-and-Interpretability-of-Contour-Lines-for-Visualizing-Multivariate-Data
Multivariate geospatial data are commonly visualized using contour plots, where the plots for various attributes are often examined side by side, or using color blending. As the number of attributes grows, however, these approaches become less efficient. This limitation motivated the use of glyphs, where different attributes are mapped to different preattentive features of the glyphs. Since both contour plot overlays and glyphs clutter the underlying map, in this paper we examine whether contour lines, which are already present in map space, can be leveraged to visualize multivariate geospatial data.   We present five different designs for stylizing contour lines, and investigate their interpretability using three crowdsourced studies. We evaluated the designs through a set of common geospatial data analysis tasks on a four-dimensional dataset. Our first two studies examined how contour width and number of contour intervals affect interpretability, using synthetic datasets where we controlled the underlying data distribution. Study 1 revealed that the increase of width improves the task performance in most of the designs, specially in completion time, except some scenarios where reducing width does not affect performance where the visibility of the background is critical. In study 2, we found out that fewer contour intervals lead to less visual clutter, hence improved performance. We then compared the designs in a third study that used both synthetic and real-world meteorological data. The study revealed that the results found using synthetic data were generalizable to the real world data, as hypothesized. Moreover, we formulated a design recommendation table tuned to give users task- and category-specific design suggestions under various environment constraints. At last, we discuss the comparison between the lab and online versions of study 1 with respect to display size (lab study was done on big screen and vice versa).  Our studies show the effectiveness of stylizing contour lines to represent multivariate data, reveal trade-offs among design parameters, and provide designers with important insights into the factors that influence multivariate interpretability.
