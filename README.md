# Recover-Source :mag_right: :bulb:

Recover-source is a powerful CLI tool that brings your JS/TS source code back to life :sparkles:. Given a directory with minified/uglified .js or .ts files along with their respective source map files, recover-source revives the original files as they were before compilation. Turn the unreadable into the understandable!

## Installation :wrench:
```bash
npm i recover-source -g
```

And that's it! Recover-source is ready for action :rocket:!

## Usage :video_game: 
To use recover-source, simply provide it with a directoy containing minified files:
```bash
recover-source -i <path-to-directory-with-minified-files>
recover-src -i <path-to-directory-with-minified-files> -o <path-to-output-directory>
git clone git@github.com:cvrobot/recover-source.git
npm install
node index_new.js -i ../../extension/kfpgookelklhphhnihipmknjdgbeecgj/0.3.0_0/js -o ../../extension/kfpgookelklhphhnihipmknjdgbeecgj/0.3.0_0/code/
node index_new.js -i ../../extension/kfpgookelklhphhnihipmknjdgbeecgj/0.3.0_0/static/css/popup.f4d6491b.css -o ../../extension/kfpgookelklhphhnihipmknjdgbeecgj/0.3.0_0/code/
```

... and watch as the original source code springs back into existence!

For more information and a step-by-step guide, check out the full tutorial here: <a href="https://www.linkedin.com/pulse/reconstructing-javascript-source-code-from-maps-schaffner-bofill">Reconstructing JavaScript Source Code from Source Maps</a>

Happy code recovery! :tada:
