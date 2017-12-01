task :dummy do
  p ENV["SEC_VAR"]
  p "abc$£def"
  IO.write("somefile.txt","abc$£def")
  IO.write("securefile.txt",ENV["SEC_VAR"])
  if ENV["SEC_VAR"] == "abc$£def"
    p "found"
  else
    raise "Failed to match"
  end
end
