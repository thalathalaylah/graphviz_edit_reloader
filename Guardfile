def change_ext(filepath, ext)
  File.dirname(filepath) + '/' + File.basename(filepath, ".*") + '.' + ext
end

guard 'shell' do
  watch(/(.*).dot/) { |s| `fdp -Tsvg #{s[0]} -o #{change_ext(s[0], 'svg')}` }
end

guard 'livereload' do
  watch(/(.*).svg/)
end
