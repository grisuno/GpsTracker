# Recipe: Reduce File Complexity

Target hotspot: `servers/dotNet/js/leaflet-0.7.5/leaflet-src.js`
(complexity 1.0, centrality 1.0)

1. Read dependents: `grep -n 'servers/dotNet/js/leaflet-0.7.5/leaflet-src.js' readmenator-agent/ARCHITECTURE.md`
2. Extract functions/classes into new files in the same subsystem
3. Update imports
4. Regenerate: `readmenator .`
