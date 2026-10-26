show_file <- \(path) {
  if (!file.exists(path)) {
    stop("File not found: ", path)
  }
  cat(readLines(path, warn = FALSE), sep = "\n")
}
