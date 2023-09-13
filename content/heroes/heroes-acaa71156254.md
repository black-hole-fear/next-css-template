---
title: Hero Section with image
category: Marketing
paid: true
isActive: true
ltr: {"vue":{"vueTail":[],"vueCss":[]},"preview":"function App() {\n  const [state, setState] = React.useState(false);\n\n  // Replace javascript:void(0) paths with your paths\n  const navigation = [{\n    title: \"Features\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"Integrations\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"Customers\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"Pricing\",\n    path: \"javascript:void(0)\"\n  }];\n  React.useEffect(() => {\n    document.onclick = e => {\n      const target = e.target;\n      if (!target.closest(\".menu-btn\")) setState(false);\n    };\n  }, []);\n  const Brand = () => /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex items-center justify-between py-5 md:block\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\"\n  }, /*#__PURE__*/React.createElement(\"img\", {\n    src: \"https://www.floatui.com/logo.svg\",\n    width: 120,\n    height: 50,\n    alt: \"Float UI logo\"\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"md:hidden\"\n  }, /*#__PURE__*/React.createElement(\"button\", {\n    className: \"menu-btn text-gray-500 hover:text-gray-800\",\n    onClick: () => setState(!state)\n  }, state ? /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-6 w-6\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  })) : /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    fill: \"none\",\n    viewBox: \"0 0 24 24\",\n    strokeWidth: 1.5,\n    stroke: \"currentColor\",\n    className: \"w-6 h-6\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    strokeLinecap: \"round\",\n    strokeLinejoin: \"round\",\n    d: \"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\"\n  })))));\n  return /*#__PURE__*/React.createElement(\"div\", {\n    className: \"relative\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"absolute inset-0 blur-xl h-[580px]\",\n    style: {\n      background: \"linear-gradient(143.6deg, rgba(192, 132, 252, 0) 20.79%, rgba(232, 121, 249, 0.26) 40.92%, rgba(204, 171, 238, 0) 70.35%)\"\n    }\n  }), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"relative\"\n  }, /*#__PURE__*/React.createElement(\"header\", null, /*#__PURE__*/React.createElement(\"div\", {\n    className: `md:hidden ${state ? \"mx-2 pb-5\" : \"hidden\"}`\n  }, /*#__PURE__*/React.createElement(Brand, null)), /*#__PURE__*/React.createElement(\"nav\", {\n    className: `pb-5 md:text-sm ${state ? \"absolute top-0 inset-x-0 bg-white shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-0 md:mt-0 md:relative md:bg-transparent\" : \"\"}`\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\"\n  }, /*#__PURE__*/React.createElement(Brand, null), /*#__PURE__*/React.createElement(\"div\", {\n    className: `flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"flex-1 justify-center items-center space-y-6 md:flex md:space-x-6 md:space-y-0\"\n  }, navigation.map((item, idx) => {\n    return /*#__PURE__*/React.createElement(\"li\", {\n      key: idx,\n      className: \"text-gray-700 hover:text-gray-900\"\n    }, /*#__PURE__*/React.createElement(\"a\", {\n      href: item.path,\n      className: \"block\"\n    }, item.title));\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"items-center justify-end mt-6 space-y-6 md:flex md:mt-0\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\"\n  }, \"Sign in\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\",\n    clipRule: \"evenodd\"\n  })))))))), /*#__PURE__*/React.createElement(\"section\", null, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-screen-xl mx-auto px-4 py-28 gap-12 text-gray-600 overflow-hidden md:px-8 md:flex\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex-none space-y-5 max-w-xl\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"inline-flex gap-x-6 items-center rounded-full p-1 pr-6 border text-sm font-medium duration-150 hover:bg-white\"\n  }, /*#__PURE__*/React.createElement(\"span\", {\n    className: \"inline-block rounded-full px-3 py-1 bg-indigo-600 text-white\"\n  }, \"News\"), /*#__PURE__*/React.createElement(\"p\", {\n    className: \"flex items-center\"\n  }, \"Read the launch post from here\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\",\n    clipRule: \"evenodd\"\n  })))), /*#__PURE__*/React.createElement(\"h1\", {\n    className: \"text-4xl text-gray-800 font-extrabold sm:text-5xl\"\n  }, \"Build your SaaS exactly how you want\"), /*#__PURE__*/React.createElement(\"p\", null, \"Sed ut perspiciatis unde omnis iste natus voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.\"), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex items-center gap-x-3 sm:text-sm\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 duration-150 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\"\n  }, \"Get started\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\",\n    clipRule: \"evenodd\"\n  }))), /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-gray-700 hover:text-gray-900 font-medium duration-150 md:inline-flex\"\n  }, \"Contact sales\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\",\n    clipRule: \"evenodd\"\n  }))))), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex-1 hidden md:block\"\n  }, /*#__PURE__*/React.createElement(\"img\", {\n    src: \"https://res.cloudinary.com/floatui/image/upload/c_pad,b_auto:predominant,fl_preserve_transparency/v1669333920/undraw_progressive_app_m-9-ms_oftfv5.jpg\",\n    className: \"max-w-xl\"\n  }))))));\n}","react":{"jsxCss":[],"jsxTail":[{"code":"import { useEffect, useState } from 'react'\n\nexport default () => {\n\n    const [state, setState] = useState(false)\n\n    // Replace javascript:void(0) paths with your paths\n    const navigation = [\n        { title: \"Features\", path: \"javascript:void(0)\" },\n        { title: \"Integrations\", path: \"javascript:void(0)\" },\n        { title: \"Customers\", path: \"javascript:void(0)\" },\n        { title: \"Pricing\", path: \"javascript:void(0)\" }\n    ]\n\n    useEffect(() => {\n        document.onclick = (e) => {\n            const target = e.target;\n            if (!target.closest(\".menu-btn\")) setState(false);\n        };\n    }, [])\n\n\n    const Brand = () => (\n        <div className=\"flex items-center justify-between py-5 md:block\">\n            <a href=\"javascript:void(0)\">\n                <img\n                    src=\"https://www.floatui.com/logo.svg\"\n                    width={120}\n                    height={50}\n                    alt=\"Float UI logo\"\n                />\n            </a>\n            <div className=\"md:hidden\">\n                <button className=\"menu-btn text-gray-500 hover:text-gray-800\"\n                    onClick={() => setState(!state)}\n                >\n                    {\n                        state ? (\n                            <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-6 w-6\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                            </svg>\n                        ) : (\n                            <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                                <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\" />\n                            </svg>\n                        )\n                    }\n                </button>\n            </div>\n        </div>\n    )\n\n    return (\n        <div className='relative'>\n            <div className='absolute inset-0 blur-xl h-[580px]' style={{ background: \"linear-gradient(143.6deg, rgba(192, 132, 252, 0) 20.79%, rgba(232, 121, 249, 0.26) 40.92%, rgba(204, 171, 238, 0) 70.35%)\" }}></div>\n            <div className='relative'>\n                <header>\n                    <div className={`md:hidden ${state ? \"mx-2 pb-5\" : \"hidden\"}`}>\n                        <Brand />\n                    </div>\n                    <nav className={`pb-5 md:text-sm ${state ? \"absolute top-0 inset-x-0 bg-white shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-0 md:mt-0 md:relative md:bg-transparent\" : \"\"}`}>\n                        <div className=\"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\">\n                            <Brand />\n                            <div className={`flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `}>\n                                <ul className=\"flex-1 justify-center items-center space-y-6 md:flex md:space-x-6 md:space-y-0\">\n                                    {\n                                        navigation.map((item, idx) => {\n                                            return (\n                                                <li key={idx} className=\"text-gray-700 hover:text-gray-900\">\n                                                    <a href={item.path} className=\"block\">\n                                                        {item.title}\n                                                    </a>\n                                                </li>\n                                            )\n                                        })\n                                    }\n                                </ul>\n                                <div className=\"items-center justify-end mt-6 space-y-6 md:flex md:mt-0\">\n                                    <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\">\n                                        Sign in\n                                        <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                            <path fillRule=\"evenodd\" d=\"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\" clipRule=\"evenodd\" />\n                                        </svg>\n                                    </a>\n                                </div>\n                            </div>\n                        </div>\n                    </nav>\n                </header>\n                <section>\n                    <div className=\"max-w-screen-xl mx-auto px-4 py-28 gap-12 text-gray-600 overflow-hidden md:px-8 md:flex\">\n                        <div className='flex-none space-y-5 max-w-xl'>\n                            <a href=\"javascript:void(0)\" className='inline-flex gap-x-6 items-center rounded-full p-1 pr-6 border text-sm font-medium duration-150 hover:bg-white'>\n                                <span className='inline-block rounded-full px-3 py-1 bg-indigo-600 text-white'>\n                                    News\n                                </span>\n                                <p className='flex items-center'>\n                                    Read the launch post from here\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                        <path fillRule=\"evenodd\" d=\"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </p>\n                            </a>\n                            <h1 className=\"text-4xl text-gray-800 font-extrabold sm:text-5xl\">\n                                Build your SaaS exactly how you want\n                            </h1>\n                            <p>\n                                Sed ut perspiciatis unde omnis iste natus voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.\n                            </p>\n                            <div className='flex items-center gap-x-3 sm:text-sm'>\n                                <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 duration-150 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\">\n                                    Get started\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                        <path fillRule=\"evenodd\" d=\"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                                <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-gray-700 hover:text-gray-900 font-medium duration-150 md:inline-flex\">\n                                    Contact sales\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                        <path fillRule=\"evenodd\" d=\"M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                            </div>\n                        </div>\n                        <div className='flex-1 hidden md:block'>\n                            {/* Replace with your image */}\n                            <img src=\"https://res.cloudinary.com/floatui/image/upload/c_pad,b_auto:predominant,fl_preserve_transparency/v1669333920/undraw_progressive_app_m-9-ms_oftfv5.jpg\" className=\"max-w-xl\" />\n                        </div>\n                    </div>\n                </section>\n            </div>\n        </div>\n    )\n}","label":"App.jsx"}]}}
rtl: {"vue":{"vueCss":[],"vueTail":[]},"react":{"jsxTail":[{"code":"import { useEffect, useState } from 'react'\n\nexport default () => {\n\n    const [state, setState] = useState(false)\n\n    // Replace javascript:void(0) paths with your paths\n    const navigation = [\n        { title: \"المميزات\", path: \"javascript:void(0)\" },\n        { title: \"التكاملات\", path: \"javascript:void(0)\" },\n        { title: \"العملاء\", path: \"javascript:void(0)\" },\n        { title: \"التسعير\", path: \"javascript:void(0)\" }\n    ]\n\n    useEffect(() => {\n        document.onclick = (e) => {\n            const target = e.target;\n            if (!target.closest(\".menu-btn\")) setState(false);\n        };\n    }, [])\n\n\n    const Brand = () => (\n        <div className=\"flex items-center justify-between py-5 md:block\">\n            <a href=\"javascript:void(0)\">\n                <img\n                    src=\"https://www.floatui.com/logo.svg\"\n                    width={120}\n                    height={50}\n                    alt=\"Float UI logo\"\n                />\n            </a>\n            <div className=\"md:hidden\">\n                <button className=\"menu-btn text-gray-500 hover:text-gray-800\"\n                    onClick={() => setState(!state)}\n                >\n                    {\n                        state ? (\n                            <svg xmlns=\"http://www.w3.org/2000/svg\" className=\"h-6 w-6\" viewBox=\"0 0 20 20\" fill=\"currentColor\">\n                                <path fillRule=\"evenodd\" d=\"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\" clipRule=\"evenodd\" />\n                            </svg>\n                        ) : (\n                            <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                                <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\" />\n                            </svg>\n                        )\n                    }\n                </button>\n            </div>\n        </div>\n    )\n\n    return (\n        <div className='relative'>\n            <div className='absolute inset-0 blur-xl h-[580px]' style={{ background: \"linear-gradient(143.6deg, rgba(192, 132, 252, 0) 20.79%, rgba(232, 121, 249, 0.26) 40.92%, rgba(204, 171, 238, 0) 70.35%)\" }}></div>\n            <div className='relative'>\n                <header>\n                    <div className={`md:hidden ${state ? \"mx-2 pb-5\" : \"hidden\"}`}>\n                        <Brand />\n                    </div>\n                    <nav className={`pb-5 md:text-sm ${state ? \"absolute top-0 inset-x-0 bg-white shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-0 md:mt-0 md:relative md:bg-transparent\" : \"\"}`}>\n                        <div className=\"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\">\n                            <Brand />\n                            <div className={`flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `}>\n                                <ul className=\"flex-1 justify-center items-center space-y-6 md:flex md:space-x-6 md:space-x-reverse md:space-y-0\">\n                                    {\n                                        navigation.map((item, idx) => {\n                                            return (\n                                                <li key={idx} className=\"text-gray-700 hover:text-gray-900\">\n                                                    <a href={item.path} className=\"block\">\n                                                        {item.title}\n                                                    </a>\n                                                </li>\n                                            )\n                                        })\n                                    }\n                                </ul>\n                                <div className=\"items-center justify-end mt-6 space-y-6 md:flex md:mt-0\">\n                                    <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\">\n                                        تسجيل دخول\n                                        <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                            <path fillRule=\"evenodd\" d=\"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\" clipRule=\"evenodd\" />\n                                        </svg>\n                                    </a>\n                                </div>\n                            </div>\n                        </div>\n                    </nav>\n                </header>\n                <section>\n                    <div className=\"max-w-screen-xl mx-auto px-4 py-28 gap-12 text-gray-600 overflow-hidden md:px-8 md:flex\">\n                        <div className='flex-none space-y-5 max-w-xl'>\n                            <a href=\"javascript:void(0)\" className='inline-flex gap-x-6 items-center rounded-full p-1 pl-6 border text-sm font-medium duration-150 hover:bg-white'>\n                                <span className='inline-block rounded-full px-3 py-1 bg-indigo-600 text-white'>\n                                    أخبار\n                                </span>\n                                <p className='flex items-center'>\n                                    اقرأ منشور الإطلاق من هنا\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                        <path fillRule=\"evenodd\" d=\"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </p>\n                            </a>\n                            <h1 className=\"text-4xl text-gray-800 font-extrabold sm:text-5xl\">\n                                قم ببناء SaaS الخاص بك بالطريقة التي تريدها بالضبط\n                            </h1>\n                            <p>\n                                ولكن لكي ترى من أين يولد كل هذا ممن يتهمون اللذة والحمد بالألم ، سأفتح الأمر برمته ، وهذه الأشياء بالذات.\n                            </p>\n                            <div className='flex items-center gap-x-3 sm:text-sm'>\n                                <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 duration-150 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\">\n                                    دعنا نبدء\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                        <path fillRule=\"evenodd\" d=\"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                                <a href=\"javascript:void(0)\" className=\"flex items-center justify-center gap-x-1 py-2 px-4 text-gray-700 hover:text-gray-900 font-medium duration-150 md:inline-flex\">\n                                    مبيعات الاتصال\n                                    <svg xmlns=\"http://www.w3.org/2000/svg\" viewBox=\"0 0 20 20\" fill=\"currentColor\" className=\"w-5 h-5\">\n                                        <path fillRule=\"evenodd\" d=\"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\" clipRule=\"evenodd\" />\n                                    </svg>\n                                </a>\n                            </div>\n                        </div>\n                        <div className='flex-1 hidden md:block'>\n                            {/* Replace with your image */}\n                            <img src=\"https://res.cloudinary.com/floatui/image/upload/c_pad,b_auto:predominant,fl_preserve_transparency/v1669333920/undraw_progressive_app_m-9-ms_oftfv5.jpg\" className=\"max-w-xl\" />\n                        </div>\n                    </div>\n                </section>\n            </div>\n        </div>\n    )\n}","label":"App.jsx"}],"jsxCss":[]},"preview":"function App() {\n  const [state, setState] = React.useState(false);\n\n  // Replace javascript:void(0) paths with your paths\n  const navigation = [{\n    title: \"المميزات\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"التكاملات\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"العملاء\",\n    path: \"javascript:void(0)\"\n  }, {\n    title: \"التسعير\",\n    path: \"javascript:void(0)\"\n  }];\n  React.useEffect(() => {\n    document.onclick = e => {\n      const target = e.target;\n      if (!target.closest(\".menu-btn\")) setState(false);\n    };\n  }, []);\n  const Brand = () => /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex items-center justify-between py-5 md:block\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\"\n  }, /*#__PURE__*/React.createElement(\"img\", {\n    src: \"https://www.floatui.com/logo.svg\",\n    width: 120,\n    height: 50,\n    alt: \"Float UI logo\"\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"md:hidden\"\n  }, /*#__PURE__*/React.createElement(\"button\", {\n    className: \"menu-btn text-gray-500 hover:text-gray-800\",\n    onClick: () => setState(!state)\n  }, state ? /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    className: \"h-6 w-6\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z\",\n    clipRule: \"evenodd\"\n  })) : /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    fill: \"none\",\n    viewBox: \"0 0 24 24\",\n    strokeWidth: 1.5,\n    stroke: \"currentColor\",\n    className: \"w-6 h-6\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    strokeLinecap: \"round\",\n    strokeLinejoin: \"round\",\n    d: \"M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5\"\n  })))));\n  return /*#__PURE__*/React.createElement(\"div\", {\n    className: \"relative\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"absolute inset-0 blur-xl h-[580px]\",\n    style: {\n      background: \"linear-gradient(143.6deg, rgba(192, 132, 252, 0) 20.79%, rgba(232, 121, 249, 0.26) 40.92%, rgba(204, 171, 238, 0) 70.35%)\"\n    }\n  }), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"relative\"\n  }, /*#__PURE__*/React.createElement(\"header\", null, /*#__PURE__*/React.createElement(\"div\", {\n    className: `md:hidden ${state ? \"mx-2 pb-5\" : \"hidden\"}`\n  }, /*#__PURE__*/React.createElement(Brand, null)), /*#__PURE__*/React.createElement(\"nav\", {\n    className: `pb-5 md:text-sm ${state ? \"absolute top-0 inset-x-0 bg-white shadow-lg rounded-xl border mx-2 mt-2 md:shadow-none md:border-none md:mx-0 md:mt-0 md:relative md:bg-transparent\" : \"\"}`\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"gap-x-14 items-center max-w-screen-xl mx-auto px-4 md:flex md:px-8\"\n  }, /*#__PURE__*/React.createElement(Brand, null), /*#__PURE__*/React.createElement(\"div\", {\n    className: `flex-1 items-center mt-8 md:mt-0 md:flex ${state ? 'block' : 'hidden'} `\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"flex-1 justify-center items-center space-y-6 md:flex md:space-x-6 md:space-x-reverse md:space-y-0\"\n  }, navigation.map((item, idx) => {\n    return /*#__PURE__*/React.createElement(\"li\", {\n      key: idx,\n      className: \"text-gray-700 hover:text-gray-900\"\n    }, /*#__PURE__*/React.createElement(\"a\", {\n      href: item.path,\n      className: \"block\"\n    }, item.title));\n  })), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"items-center justify-end mt-6 space-y-6 md:flex md:mt-0\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\"\n  }, \"\\u062A\\u0633\\u062C\\u064A\\u0644 \\u062F\\u062E\\u0648\\u0644\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\",\n    clipRule: \"evenodd\"\n  })))))))), /*#__PURE__*/React.createElement(\"section\", null, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-screen-xl mx-auto px-4 py-28 gap-12 text-gray-600 overflow-hidden md:px-8 md:flex\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex-none space-y-5 max-w-xl\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"inline-flex gap-x-6 items-center rounded-full p-1 pl-6 border text-sm font-medium duration-150 hover:bg-white\"\n  }, /*#__PURE__*/React.createElement(\"span\", {\n    className: \"inline-block rounded-full px-3 py-1 bg-indigo-600 text-white\"\n  }, \"\\u0623\\u062E\\u0628\\u0627\\u0631\"), /*#__PURE__*/React.createElement(\"p\", {\n    className: \"flex items-center\"\n  }, \"\\u0627\\u0642\\u0631\\u0623 \\u0645\\u0646\\u0634\\u0648\\u0631 \\u0627\\u0644\\u0625\\u0637\\u0644\\u0627\\u0642 \\u0645\\u0646 \\u0647\\u0646\\u0627\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\",\n    clipRule: \"evenodd\"\n  })))), /*#__PURE__*/React.createElement(\"h1\", {\n    className: \"text-4xl text-gray-800 font-extrabold sm:text-5xl\"\n  }, \"\\u0642\\u0645 \\u0628\\u0628\\u0646\\u0627\\u0621 SaaS \\u0627\\u0644\\u062E\\u0627\\u0635 \\u0628\\u0643 \\u0628\\u0627\\u0644\\u0637\\u0631\\u064A\\u0642\\u0629 \\u0627\\u0644\\u062A\\u064A \\u062A\\u0631\\u064A\\u062F\\u0647\\u0627 \\u0628\\u0627\\u0644\\u0636\\u0628\\u0637\"), /*#__PURE__*/React.createElement(\"p\", null, \"\\u0648\\u0644\\u0643\\u0646 \\u0644\\u0643\\u064A \\u062A\\u0631\\u0649 \\u0645\\u0646 \\u0623\\u064A\\u0646 \\u064A\\u0648\\u0644\\u062F \\u0643\\u0644 \\u0647\\u0630\\u0627 \\u0645\\u0645\\u0646 \\u064A\\u062A\\u0647\\u0645\\u0648\\u0646 \\u0627\\u0644\\u0644\\u0630\\u0629 \\u0648\\u0627\\u0644\\u062D\\u0645\\u062F \\u0628\\u0627\\u0644\\u0623\\u0644\\u0645 \\u060C \\u0633\\u0623\\u0641\\u062A\\u062D \\u0627\\u0644\\u0623\\u0645\\u0631 \\u0628\\u0631\\u0645\\u062A\\u0647 \\u060C \\u0648\\u0647\\u0630\\u0647 \\u0627\\u0644\\u0623\\u0634\\u064A\\u0627\\u0621 \\u0628\\u0627\\u0644\\u0630\\u0627\\u062A.\"), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex items-center gap-x-3 sm:text-sm\"\n  }, /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-white font-medium bg-gray-800 duration-150 hover:bg-gray-700 active:bg-gray-900 rounded-full md:inline-flex\"\n  }, \"\\u062F\\u0639\\u0646\\u0627 \\u0646\\u0628\\u062F\\u0621\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\",\n    clipRule: \"evenodd\"\n  }))), /*#__PURE__*/React.createElement(\"a\", {\n    href: \"javascript:void(0)\",\n    className: \"flex items-center justify-center gap-x-1 py-2 px-4 text-gray-700 hover:text-gray-900 font-medium duration-150 md:inline-flex\"\n  }, \"\\u0645\\u0628\\u064A\\u0639\\u0627\\u062A \\u0627\\u0644\\u0627\\u062A\\u0635\\u0627\\u0644\", /*#__PURE__*/React.createElement(\"svg\", {\n    xmlns: \"http://www.w3.org/2000/svg\",\n    viewBox: \"0 0 20 20\",\n    fill: \"currentColor\",\n    className: \"w-5 h-5\"\n  }, /*#__PURE__*/React.createElement(\"path\", {\n    fillRule: \"evenodd\",\n    d: \"M12.79 5.23a.75.75 0 01-.02 1.06L8.832 10l3.938 3.71a.75.75 0 11-1.04 1.08l-4.5-4.25a.75.75 0 010-1.08l4.5-4.25a.75.75 0 011.06.02z\",\n    clipRule: \"evenodd\"\n  }))))), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"flex-1 hidden md:block\"\n  }, /*#__PURE__*/React.createElement(\"img\", {\n    src: \"https://res.cloudinary.com/floatui/image/upload/c_pad,b_auto:predominant,fl_preserve_transparency/v1669333920/undraw_progressive_app_m-9-ms_oftfv5.jpg\",\n    className: \"max-w-xl\"\n  }))))));\n}"}
slug: /heroes
id: 4514c184-535e-4630-af28-acaa71156254
created_at: 1670149507993
---