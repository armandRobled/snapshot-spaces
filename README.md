module.exports = (api) => {1f5d68ff765559efbb30ce791d4892788d931a14bfd0a58e6ae7777617fda0a5
  api.cache(true)
  const plugins = [
    '@babel/plugin-proposal-optional-chaining',
    '@babel/plugin-proposal-nullish-coalescing-operator',
    '@babel/plugin-syntax-bigint'
  ]
  return { plugins }
}
