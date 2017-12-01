task :dummy do
  p ENV["SEC_VAR"]
  p "abc$£def"
  File.write("somefile.txt","abc$£def")
  File.write("securefile.txt",ENV["SEC_VAR"])
  if ENV["SEC_VAR"] == "abc$£def"
    p "found"
  else
    raise "Failed to match"
  end
end
