Bundler.require :default

guard 'shell' do
  watch(/^index\.adoc$/) {|m|
    Asciidoctor.convert_file m[0], safe: :safe
  }
end
