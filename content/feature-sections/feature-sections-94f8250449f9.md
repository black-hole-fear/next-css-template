---
title: Divided Feature Section
category: Marketing
paid: true
isActive: true
ltr: {"preview":"function App() {\n  const features = [{\n    icon: /*#__PURE__*/React.createElement(\"svg\", {\n      xmlns: \"http://www.w3.org/2000/svg\",\n      fill: \"none\",\n      viewBox: \"0 0 24 24\",\n      strokeWidth: 1.5,\n      stroke: \"currentColor\",\n      className: \"w-6 h-6\"\n    }, /*#__PURE__*/React.createElement(\"path\", {\n      strokeLinecap: \"round\",\n      strokeLinejoin: \"round\",\n      d: \"M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z\"\n    })),\n    title: \"Analytics\",\n    desc: \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius.\"\n  }, {\n    icon: /*#__PURE__*/React.createElement(\"svg\", {\n      xmlns: \"http://www.w3.org/2000/svg\",\n      fill: \"none\",\n      viewBox: \"0 0 24 24\",\n      strokeWidth: 1.5,\n      stroke: \"currentColor\",\n      className: \"w-6 h-6\"\n    }, /*#__PURE__*/React.createElement(\"path\", {\n      strokeLinecap: \"round\",\n      strokeLinejoin: \"round\",\n      d: \"M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z\"\n    })),\n    title: \"Datacenter security\",\n    desc: \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius.\"\n  }, {\n    icon: /*#__PURE__*/React.createElement(\"svg\", {\n      xmlns: \"http://www.w3.org/2000/svg\",\n      fill: \"none\",\n      viewBox: \"0 0 24 24\",\n      strokeWidth: 1.5,\n      stroke: \"currentColor\",\n      className: \"w-6 h-6\"\n    }, /*#__PURE__*/React.createElement(\"path\", {\n      strokeLinecap: \"round\",\n      strokeLinejoin: \"round\",\n      d: \"M6.429 9.75L2.25 12l4.179 2.25m0-4.5l5.571 3 5.571-3m-11.142 0L2.25 7.5 12 2.25l9.75 5.25-4.179 2.25m0 0L21.75 12l-4.179 2.25m0 0l4.179 2.25L12 21.75 2.25 16.5l4.179-2.25m11.142 0l-5.571 3-5.571-3\"\n    })),\n    title: \"Build on your terms\",\n    desc: \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius.\"\n  }];\n  return /*#__PURE__*/React.createElement(\"section\", {\n    className: \"py-14\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-screen-xl mx-auto px-4 text-gray-600 md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-xl space-y-3\"\n  }, /*#__PURE__*/React.createElement(\"h3\", {\n    className: \"text-indigo-600 font-semibold\"\n  }, \"Features\"), /*#__PURE__*/React.createElement(\"p\", {\n    className: \"text-gray-800 text-3xl font-semibold sm:text-4xl\"\n  }, \"Do more with less complexity\"), /*#__PURE__*/React.createElement(\"p\", null, \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius\")), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-12\"\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"grid gap-x-12 divide-y [&>.feature-1]:pl-0 sm:grid-cols-2 sm:gap-y-8 sm:divide-y-0 lg:divide-x lg:grid-cols-3 lg:gap-x-0\"\n  }, features.map((item, idx) => /*#__PURE__*/React.createElement(\"li\", {\n    key: idx,\n    className: `feature-${idx + 1} space-y-3 py-8 lg:px-12 sm:py-0`\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"w-12 h-12 border text-indigo-600 rounded-full flex items-center justify-center\"\n  }, item.icon), /*#__PURE__*/React.createElement(\"h4\", {\n    className: \"text-lg text-gray-800 font-semibold\"\n  }, item.title), /*#__PURE__*/React.createElement(\"p\", null, item.desc)))))));\n}","vue":{"vueTail":[],"vueCss":[]},"react":{"jsxTail":[{"code":"export default () => {\n\n    const features = [\n        {\n            icon:\n                <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                    <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z\" />\n                </svg>,\n            title: \"Analytics\",\n            desc: \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius.\"\n        },\n        {\n            icon:\n                <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                    <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z\" />\n                </svg>,\n            title: \"Datacenter security\",\n            desc: \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius.\"\n        },\n        {\n            icon:\n                <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                    <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M6.429 9.75L2.25 12l4.179 2.25m0-4.5l5.571 3 5.571-3m-11.142 0L2.25 7.5 12 2.25l9.75 5.25-4.179 2.25m0 0L21.75 12l-4.179 2.25m0 0l4.179 2.25L12 21.75 2.25 16.5l4.179-2.25m11.142 0l-5.571 3-5.571-3\" />\n                </svg>,\n            title: \"Build on your terms\",\n            desc: \"Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius.\"\n        }\n    ]\n\n    return (\n        <section className=\"py-14\">\n            <div className=\"max-w-screen-xl mx-auto px-4 text-gray-600 md:px-8\">\n                <div className=\"max-w-xl space-y-3\">\n                    <h3 className=\"text-indigo-600 font-semibold\">\n                        Features\n                    </h3>\n                    <p className=\"text-gray-800 text-3xl font-semibold sm:text-4xl\">\n                        Do more with less complexity\n                    </p>\n                    <p>\n                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec congue, nisl eget molestie varius\n                    </p>\n                </div>\n                <div className=\"mt-12\">\n                    <ul className=\"grid gap-x-12 divide-y [&>.feature-1]:pl-0 sm:grid-cols-2 sm:gap-y-8 sm:divide-y-0 lg:divide-x lg:grid-cols-3 lg:gap-x-0\">\n                        {\n                            features.map((item, idx) => (\n                                <li key={idx} className={`feature-${idx + 1} space-y-3 py-8 lg:px-12 sm:py-0`}>\n                                    <div className=\"w-12 h-12 border text-indigo-600 rounded-full flex items-center justify-center\">\n                                        {item.icon}\n                                    </div>\n                                    <h4 className=\"text-lg text-gray-800 font-semibold\">\n                                        {item.title}\n                                    </h4>\n                                    <p>\n                                        {item.desc}\n                                    </p>\n                                </li>\n                            ))\n                        }\n                    </ul>\n                </div>\n            </div>\n        </section>\n    )\n}","label":"App.jsx"}],"jsxCss":[]}}
rtl: {"vue":{"vueCss":[],"vueTail":[]},"preview":"function App() {\n  const features = [{\n    icon: /*#__PURE__*/React.createElement(\"svg\", {\n      xmlns: \"http://www.w3.org/2000/svg\",\n      fill: \"none\",\n      viewBox: \"0 0 24 24\",\n      strokeWidth: 1.5,\n      stroke: \"currentColor\",\n      className: \"w-6 h-6\"\n    }, /*#__PURE__*/React.createElement(\"path\", {\n      strokeLinecap: \"round\",\n      strokeLinejoin: \"round\",\n      d: \"M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z\"\n    })),\n    title: \"التحليلات\",\n    desc: \"العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين.\"\n  }, {\n    icon: /*#__PURE__*/React.createElement(\"svg\", {\n      xmlns: \"http://www.w3.org/2000/svg\",\n      fill: \"none\",\n      viewBox: \"0 0 24 24\",\n      strokeWidth: 1.5,\n      stroke: \"currentColor\",\n      className: \"w-6 h-6\"\n    }, /*#__PURE__*/React.createElement(\"path\", {\n      strokeLinecap: \"round\",\n      strokeLinejoin: \"round\",\n      d: \"M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z\"\n    })),\n    title: \"أمن مركز البيانات\",\n    desc: \"العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين.\"\n  }, {\n    icon: /*#__PURE__*/React.createElement(\"svg\", {\n      xmlns: \"http://www.w3.org/2000/svg\",\n      fill: \"none\",\n      viewBox: \"0 0 24 24\",\n      strokeWidth: 1.5,\n      stroke: \"currentColor\",\n      className: \"w-6 h-6\"\n    }, /*#__PURE__*/React.createElement(\"path\", {\n      strokeLinecap: \"round\",\n      strokeLinejoin: \"round\",\n      d: \"M6.429 9.75L2.25 12l4.179 2.25m0-4.5l5.571 3 5.571-3m-11.142 0L2.25 7.5 12 2.25l9.75 5.25-4.179 2.25m0 0L21.75 12l-4.179 2.25m0 0l4.179 2.25L12 21.75 2.25 16.5l4.179-2.25m11.142 0l-5.571 3-5.571-3\"\n    })),\n    title: \"بناء على شروطك\",\n    desc: \"العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين.\"\n  }];\n  return /*#__PURE__*/React.createElement(\"section\", {\n    className: \"py-14\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-screen-xl mx-auto px-4 text-gray-600 md:px-8\"\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"max-w-xl space-y-3\"\n  }, /*#__PURE__*/React.createElement(\"h3\", {\n    className: \"text-indigo-600 font-semibold\"\n  }, \"\\u0627\\u0644\\u0645\\u0645\\u064A\\u0632\\u0627\\u062A\"), /*#__PURE__*/React.createElement(\"p\", {\n    className: \"text-gray-800 text-3xl font-semibold sm:text-4xl\"\n  }, \"\\u0627\\u0641\\u0639\\u0644 \\u0627\\u0644\\u0645\\u0632\\u064A\\u062F \\u0645\\u0639 \\u0642\\u062F\\u0631 \\u0623\\u0642\\u0644 \\u0645\\u0646 \\u0627\\u0644\\u062A\\u0639\\u0642\\u064A\\u062F\"), /*#__PURE__*/React.createElement(\"p\", null, \"\\u0627\\u0644\\u0639\\u0645\\u064A\\u0644 \\u0645\\u0647\\u0645 \\u062C\\u062F\\u0627 \\u060C \\u0627\\u0644\\u0639\\u0645\\u064A\\u0644 \\u0633\\u064A\\u062A\\u0628\\u0639\\u0647. \\u062D\\u062A\\u0649 \\u0627\\u0644\\u0648\\u0627\\u062C\\u0628 \\u0627\\u0644\\u0645\\u0646\\u0632\\u0644\\u064A \\u060C \\u064A\\u062D\\u062A\\u0627\\u062C \\u0627\\u0644\\u0644\\u0627\\u0639\\u0628\\u0648\\u0646 \\u0625\\u0644\\u0649 \\u0645\\u0648\\u0638\\u0641\\u064A\\u0646 \\u0645\\u062E\\u062A\\u0644\\u0641\\u064A\\u0646\")), /*#__PURE__*/React.createElement(\"div\", {\n    className: \"mt-12\"\n  }, /*#__PURE__*/React.createElement(\"ul\", {\n    className: \"grid gap-x-12 divide-y [&>.feature-1]:pr-0 sm:grid-cols-2 sm:gap-y-8 sm:divide-y-0 lg:divide-x lg:divide-x-reverse lg:grid-cols-3 lg:gap-x-0\"\n  }, features.map((item, idx) => /*#__PURE__*/React.createElement(\"li\", {\n    key: idx,\n    className: `feature-${idx + 1} space-y-3 py-8 lg:px-12 sm:py-0`\n  }, /*#__PURE__*/React.createElement(\"div\", {\n    className: \"w-12 h-12 border text-indigo-600 rounded-full flex items-center justify-center\"\n  }, item.icon), /*#__PURE__*/React.createElement(\"h4\", {\n    className: \"text-lg text-gray-800 font-semibold\"\n  }, item.title), /*#__PURE__*/React.createElement(\"p\", null, item.desc)))))));\n}","react":{"jsxCss":[],"jsxTail":[{"code":"export default () => {\n\n    const features = [\n        {\n            icon:\n                <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                    <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M3 13.125C3 12.504 3.504 12 4.125 12h2.25c.621 0 1.125.504 1.125 1.125v6.75C7.5 20.496 6.996 21 6.375 21h-2.25A1.125 1.125 0 013 19.875v-6.75zM9.75 8.625c0-.621.504-1.125 1.125-1.125h2.25c.621 0 1.125.504 1.125 1.125v11.25c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V8.625zM16.5 4.125c0-.621.504-1.125 1.125-1.125h2.25C20.496 3 21 3.504 21 4.125v15.75c0 .621-.504 1.125-1.125 1.125h-2.25a1.125 1.125 0 01-1.125-1.125V4.125z\" />\n                </svg>,\n            title: \"التحليلات\",\n            desc: \"العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين.\"\n        },\n        {\n            icon:\n                <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                    <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M16.5 10.5V6.75a4.5 4.5 0 10-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 002.25-2.25v-6.75a2.25 2.25 0 00-2.25-2.25H6.75a2.25 2.25 0 00-2.25 2.25v6.75a2.25 2.25 0 002.25 2.25z\" />\n                </svg>,\n            title: \"أمن مركز البيانات\",\n            desc: \"العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين.\"\n        },\n        {\n            icon:\n                <svg xmlns=\"http://www.w3.org/2000/svg\" fill=\"none\" viewBox=\"0 0 24 24\" strokeWidth={1.5} stroke=\"currentColor\" className=\"w-6 h-6\">\n                    <path strokeLinecap=\"round\" strokeLinejoin=\"round\" d=\"M6.429 9.75L2.25 12l4.179 2.25m0-4.5l5.571 3 5.571-3m-11.142 0L2.25 7.5 12 2.25l9.75 5.25-4.179 2.25m0 0L21.75 12l-4.179 2.25m0 0l4.179 2.25L12 21.75 2.25 16.5l4.179-2.25m11.142 0l-5.571 3-5.571-3\" />\n                </svg>,\n            title: \"بناء على شروطك\",\n            desc: \"العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين.\"\n        }\n    ]\n\n    return (\n        <section className=\"py-14\">\n            <div className=\"max-w-screen-xl mx-auto px-4 text-gray-600 md:px-8\">\n                <div className=\"max-w-xl space-y-3\">\n                    <h3 className=\"text-indigo-600 font-semibold\">\n                        المميزات\n                    </h3>\n                    <p className=\"text-gray-800 text-3xl font-semibold sm:text-4xl\">\n                        افعل المزيد مع قدر أقل من التعقيد\n                    </p>\n                    <p>\n                        العميل مهم جدا ، العميل سيتبعه. حتى الواجب المنزلي ، يحتاج اللاعبون إلى موظفين مختلفين\n                    </p>\n                </div>\n                <div className=\"mt-12\">\n                    <ul className=\"grid gap-x-12 divide-y [&>.feature-1]:pr-0 sm:grid-cols-2 sm:gap-y-8 sm:divide-y-0 lg:divide-x lg:divide-x-reverse lg:grid-cols-3 lg:gap-x-0\">\n                        {\n                            features.map((item, idx) => (\n                                <li key={idx} className={`feature-${idx + 1} space-y-3 py-8 lg:px-12 sm:py-0`}>\n                                    <div className=\"w-12 h-12 border text-indigo-600 rounded-full flex items-center justify-center\">\n                                        {item.icon}\n                                    </div>\n                                    <h4 className=\"text-lg text-gray-800 font-semibold\">\n                                        {item.title}\n                                    </h4>\n                                    <p>\n                                        {item.desc}\n                                    </p>\n                                </li>\n                            ))\n                        }\n                    </ul>\n                </div>\n            </div>\n        </section>\n    )\n}","label":"App.jsx"}]}}
slug: /feature-sections
id: 891a42ff-0df3-4c02-baa8-94f8250449f9
created_at: 1671318787872
---