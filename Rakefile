task :dummy do
  p ENV["SEC_VAR"]
  p "abc$£def"
  if ENV["SEC_VAR"] == "abc$£def"
    p "found"
  else
    raise "Failed to match"
  end
end
