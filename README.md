erb preprocessor + sourcemaps bug when //= comment are used

    # bundle install
    # RAILS_ENV=production rake assets:precompile
    
    # cat public/assets/application-*.js
    let test4_js = null;
    let test3_js = null;
    let test2_js = null;
    let test1_js = null;
    let application_js = null;
    
    # cat cat public/assets/application.js-*.map
    {"version":3,"file":"application.js","sections":[{"offset":{"line":0,"column":0},"map":{"version":3,"file":"test4.js.erb","mappings":"AAAA;AACA","sources":["test4.source.js.erb"],"names":[]}},{"offset":{"line":2,"column":0},"map":{"version":3,"file":"test3.js","mappings":"AAAA","sources":["test3.source.js"],"names":[]}},{"offset":{"line":3,"column":0},"map":{"version":3,"file":"test2.js","mappings":"AAAA","sources":["test2.source.js"],"names":[]}},{"offset":{"line":4,"column":0},"map":{"version":3,"file":"test1.js.erb","mappings":"AAAA;AACA","sources":["test1.source.js.erb"],"names":[]}},{"offset":{"line":6,"column":0},"map":{"version":3,"file":"application.js","mappings":"AAAA","sources":["application.source.js"],"names":[],"x_sprockets_linecount":1}}]}
