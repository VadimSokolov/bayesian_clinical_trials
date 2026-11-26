# Book renders use knitr's chunk cache. A cached chunk does not re-run its library() calls,
# so the packages the chapters use are attached here, and the cache is invalidated
# whenever the bayestrials package is reinstalled.
local({
  for (p in c("bayestrials", "ggplot2", "patchwork", "knitr", "SampleSizeProportions"))
    if (requireNamespace(p, quietly = TRUE)) suppressPackageStartupMessages(library(p, character.only = TRUE))
  rdb <- tryCatch(file.path(find.package("bayestrials", quiet = TRUE), "R", "bayestrials.rdb"), error = function(e) "")
  if (length(rdb) == 1 && nzchar(rdb) && file.exists(rdb) && requireNamespace("knitr", quietly = TRUE))
    knitr::opts_chunk$set(cache.extra = unname(tools::md5sum(rdb)))
})
