import React, { useState, useEffect } from "react";

const App = () => {
  const [selectedTab, setSelectedTab] = useState('accueil');
  const [selectedCountry, setSelectedCountry] = useState('Côte d\'Ivoire');
  const [searchQuery, setSearchQuery] = useState('');
  const [activeSubTab, setActiveSubTab] = useState('equipe_nationale');

  // Liste des pays africains
  const paysAfricains = [
    'Côte d\'Ivoire', 'Ghana', 'Nigeria', 'Sénégal', 'Cameroun', 'RD Congo', 
    'Tanzanie', 'Égypte', 'Maroc', 'Tunisie', 'Algérie', 'Libye', 'Mali', 
    'Burkina Faso', 'Afrique du Sud', 'Kenya'
  ];

  // Données mock pour Côte d'Ivoire
  const donneesPays = {
    'Côte d\'Ivoire': {
      equipeNationale: {
        nom: "Équipe de Côte d'Ivoire",
        surnom: "Les Éléphants",
        entraineur: "Jean-Louis Gasset",
        classementFIFA: 56,
        trophes: [
          { nom: "Coupe d'Afrique des Nations", annees: [1992, 2015] },
          { nom: "Coupe d'Afrique des Nations U-23", annees: [2023] }
        ],
        joueurs: [
          { nom: "Sébastien Haller", position: "Attaquant", age: 29, club: "Borussia Dortmund" },
          { nom: "Franck Kessié", position: "Milieu", age: 27, club: "Al-Ahli" },
          { nom: "Nicolas Pépé", position: "Ailier", age: 28, club: "OGC Nice" }
        ]
      },
      ligues: [
        { nom: "Ligue 1 MTN", niveau: 1, clubs: 16, championActuel: "ASEC Mimosas" },
        { nom: "Ligue 2", niveau: 2, clubs: 18, championActuel: "AS Indenié" },
        { nom: "Division 3", niveau: 3, clubs: 20, championActuel: "CO Bouaflé" },
        { nom: "Ligue Amateur 1", niveau: 4, clubs: 24, championActuel: "USC Bassam" },
        { nom: "Ligue Amateur 2", niveau: 5, clubs: 30, championActuel: "JCAT" }
      ],
      joueursLigues: [
        { nom: "Jean-Philippe Krasso", club: "RC Lens", position: "Attaquant", age: 29 },
        { nom: "Simon Deli", club: "Africa Sports", position: "Défenseur", age: 32 },
        { nom: "Max Gradel", club: "Séwé Sport", position: "Ailier", age: 36 }
      ],
      centresFormation: [
        { nom: "Académie JMG ASEC Mimosas", ville: "Abidjan", fondateur: "Jean-Marc Guillou", anneeCreation: 1999 },
        { nom: "Centre de Formation de l'ASE", ville: "Abidjan", fondateur: "Roger Ouégnin", anneeCreation: 2005 },
        { nom: "Académie de Football de Yopougon", ville: "Abidjan", fondateur: "Mamadou Coulibaly", anneeCreation: 2010 }
      ]
    }
  };

  // Données des clubs
  const clubs = [
    {
      id: 1,
      nom: "ASEC Mimosas",
      pays: "Côte d'Ivoire",
      ville: "Abidjan",
      stade: "Stade Félix Houphouët-Boigny",
      capacite: 60000,
      fondation: 1948,
      president: "Roger Ouégnin",
      entraineur: "Mohamed Magassouba",
      logo: "https://placehold.co/80x80/0066cc/ffffff?text=ASEC",
      joueurs: 25,
      valeur: "8.5M€",
      trophes: [
        { competition: "Ligue 1", nombre: 29, dernier: 2023 },
        { competition: "Coupe de Côte d'Ivoire", nombre: 10, dernier: 2022 },
        { competition: "Coupe d'Afrique des Clubs Champions", nombre: 1, dernier: 1998 }
      ]
    },
    {
      id: 2,
      nom: "Africa Sports",
      pays: "Côte d'Ivoire",
      ville: "Abidjan",
      stade: "Stade Félix Houphouët-Boigny",
      capacite: 60000,
      fondation: 1947,
      president: "Seydou Diallo",
      entraineur: "Jean-Marc Guillou",
      logo: "https://placehold.co/80x80/e60013/ffffff?text=AFRI",
      joueurs: 23,
      valeur: "6.2M€",
      trophes: [
        { competition: "Ligue 1", nombre: 17, dernier: 2021 },
        { competition: "Coupe de Côte d'Ivoire", nombre: 12, dernier: 2020 }
      ]
    }
  ];

  // Données des joueurs détaillées
  const joueurs = [
    {
      id: 1,
      nom: "Sébastien Haller",
      prenoms: "Sébastien",
      dateNaissance: "22/06/1994",
      lieuNaissance: "Fontainebleau, France",
      taille: 186,
      poids: 83,
      piedFort: "Droit",
      positions: ["Attaquant", "Avant-centre"],
      nationalites: ["Côte d'Ivoire", "France"],
      clubActuel: "Borussia Dortmund",
      agent: "Pini Zahavi",
      equipesFormation: ["AJ Auxerre", "Utrecht"],
      equipesCarriere: [
        { club: "AJ Auxerre", debut: "2011", fin: "2015", matchs: 89, buts: 23 },
        { club: "Utrecht", debut: "2015", fin: "2017", matchs: 69, buts: 30 },
        { club: "Eintracht Francfort", debut: "2017", fin: "2019", matchs: 45, buts: 15 },
        { club: "West Ham United", debut: "2019", fin: "2021", matchs: 17, buts: 1 },
        { club: "Ajax Amsterdam", debut: "2021", fin: "2023", matchs: 58, buts: 47 },
        { club: "Borussia Dortmund", debut: "2023", fin: "présent", matchs: 35, buts: 18 }
      ],
      palmares: [
        "Coupe d'Allemagne (2023)",
        "Europa League (2023)",
        "Championnat des Pays-Bas (2022)",
        "Supercoupe des Pays-Bas (2022)"
      ],
      selectionneur: true,
      equipeNationale: "Côte d'Ivoire",
      matchsAN: 45,
      butsAN: 18,
      blessure: false,
      suiviPar: ["Manchester United", "Bayern Munich"],
      statsSaison: {
        matchsJoues: 28,
        buts: 15,
        passesDecisives: 6,
        moyenneButs: 0.54,
        moyenneGeneral: 7.8
      }
    }
  ];

  // Officiels
  const officiels = [
    {
      id: 1,
      nom: "Jean-Louis Gasset",
      fonction: "Sélectionneur",
      dateNaissance: "07/09/1953",
      lieuNaissance: "Nîmes, France",
      nationalite: "France",
      experience: [
        { poste: "Sélectionneur", equipe: "Côte d'Ivoire", debut: "2022", fin: "présent" },
        { poste: "Entraîneur", equipe: "Stade Rennais", debut: "2020", fin: "2022" },
        { poste: "Directeur sportif", equipe: "Olympique Lyonnais", debut: "2019", fin: "2020" }
      ],
      palmares: [
        "Coupe de France (2019)",
        "Coupe de la Ligue (2014)"
      ],
      photo: "https://placehold.co/80x80/333333/ffffff?text=JG"
    }
  ];

  // Blog
  const articlesBlog = [
    {
      id: 1,
      titre: "Sébastien Haller, l'éléphant qui domine la Bundesliga",
      auteur: "Kouamé Diaby",
      date: "15/01/2024",
      image: "https://placehold.co/400x200/228b22/ffffff?text=Sébastien+Haller",
      resume: "Le buteur ivoirien continue d'inscrire son nom au tableau des marqueurs en Allemagne...",
      contenu: "Sébastien Haller, l'attaquant emblématique de la sélection ivoirienne, connaît une saison exceptionnelle avec Borussia Dortmund. Après avoir surmonté un cancer des testicules en 2021, Haller a fait un retour remarquable sur les terrains européens. Cette saison, il a déjà inscrit 18 buts en 28 matchs, devenant l'un des principaux artisans du succès de son équipe. Son impact ne se limite pas aux buts, mais également à son leadership sur le terrain et son implication défensive. À 29 ans, Haller est à son apogée et pourrait jouer un rôle crucial lors de la prochaine Coupe d'Afrique des Nations."
    },
    {
      id: 2,
      titre: "L'essor du football féminin en Côte d'Ivoire",
      auteur: "Adama Coulibaly",
      date: "10/01/2024",
      image: "https://placehold.co/400x200/dc143c/ffffff?text=Football+Féminin",
      resume: "Le football féminin connaît un développement fulgurant en Côte d'Ivoire...",
      contenu: "Depuis la création de la Ligue de Football Féminin en 2020, le football féminin en Côte d'Ivoire a connu une croissance exponentielle. Le nombre de licenciées est passé de 1,200 en 2019 à plus de 8,500 en 2023. La sélection nationale féminine, surnommée les 'Éléphantes', a réalisé une performance remarquable lors de la dernière CAN féminine, atteignant les quarts de finale. Ce développement est soutenu par des initiatives publiques et privées visant à promouvoir le sport féminin et à créer des opportunités pour les jeunes filles."
    }
  ];

  const filteredArticles = articlesBlog.filter(article => 
    article.titre.toLowerCase().includes(searchQuery.toLowerCase()) ||
    article.resume.toLowerCase().includes(searchQuery.toLowerCase()) ||
    article.auteur.toLowerCase().includes(searchQuery.toLowerCase())
  );

  const renderAccueil = () => (
    <div className="space-y-8">
      {/* Hero Section */}
      <div className="bg-gradient-to-r from-green-500 via-blue-600 to-orange-500 rounded-2xl shadow-xl overflow-hidden text-white">
        <div className="px-8 py-16 md:px-16 md:py-20">
          <div className="max-w-4xl">
            <h2 className="text-4xl md:text-5xl font-bold mb-4">Le Football Africain à Portée de Main</h2>
            <p className="text-xl mb-8 opacity-90">Toutes les informations sur les équipes nationales, clubs, joueurs et officiels du football africain en un seul endroit.</p>
            <div className="flex flex-wrap gap-4">
              <button 
                onClick={() => setSelectedTab('pays')}
                className="bg-white text-green-600 px-6 py-3 rounded-lg font-semibold hover:bg-gray-100 transition-colors duration-200"
              >
                Explorer les pays
              </button>
              <button 
                onClick={() => setSelectedTab('clubs')}
                className="bg-transparent border-2 border-white text-white px-6 py-3 rounded-lg font-semibold hover:bg-white hover:text-green-600 transition-colors duration-200"
              >
                Découvrir les clubs
              </button>
            </div>
          </div>
        </div>
      </div>

      {/* Stats Cards */}
      <div className="grid grid-cols-1 md:grid-cols-4 gap-6">
        <div className="bg-white rounded-xl shadow-lg p-6 text-center">
          <div className="text-3xl font-bold text-green-600 mb-2">{paysAfricains.length}</div>
          <div className="text-gray-600">Pays Africains</div>
        </div>
        <div className="bg-white rounded-xl shadow-lg p-6 text-center">
          <div className="text-3xl font-bold text-blue-600 mb-2">{clubs.length}</div>
          <div className="text-gray-600">Clubs</div>
        </div>
        <div className="bg-white rounded-xl shadow-lg p-6 text-center">
          <div className="text-3xl font-bold text-orange-600 mb-2">{joueurs.length}</div>
          <div className="text-gray-600">Joueurs</div>
        </div>
        <div className="bg-white rounded-xl shadow-lg p-6 text-center">
          <div className="text-3xl font-bold text-purple-600 mb-2">{officiels.length}</div>
          <div className="text-gray-600">Officiels</div>
        </div>
      </div>

      {/* Featured Article */}
      <div className="bg-white rounded-xl shadow-lg overflow-hidden">
        <div className="md:flex">
          <div className="md:w-1/3">
            <img src={articlesBlog[0].image} alt={articlesBlog[0].titre} className="w-full h-64 md:h-full object-cover" />
          </div>
          <div className="p-6 md:w-2/3">
            <div className="flex items-center mb-3">
              <span className="text-sm text-gray-500">{articlesBlog[0].date}</span>
              <span className="mx-2">•</span>
              <span className="text-sm text-green-600">Par {articlesBlog[0].auteur}</span>
            </div>
            <h3 className="text-2xl font-bold text-gray-800 mb-3">{articlesBlog[0].titre}</h3>
            <p className="text-gray-600 mb-4">{articlesBlog[0].resume}</p>
            <button 
              onClick={() => {
                setSelectedTab('blog');
                setActiveSubTab(articlesBlog[0].id);
              }}
              className="text-green-600 font-semibold hover:text-green-800 transition-colors duration-200"
            >
              Lire la suite →
            </button>
          </div>
        </div>
      </div>
    </div>
  );

  const renderPays = () => (
    <div className="space-y-6">
      <div className="flex flex-col md:flex-row justify-between items-start md:items-center mb-6">
        <h2 className="text-3xl font-bold text-gray-800 mb-4 md:mb-0">Pays Africains</h2>
        <div className="relative w-full md:w-64">
          <select
            value={selectedCountry}
            onChange={(e) => setSelectedCountry(e.target.value)}
            className="w-full px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-green-500"
          >
            {paysAfricains.map(pays => (
              <option key={pays} value={pays}>{pays}</option>
            ))}
          </select>
        </div>
      </div>

      {/* Sub-tabs */}
      <div className="flex space-x-1 mb-6">
        {[
          { id: 'equipe_nationale', label: 'Équipe Nationale', icon: '🏆' },
          { id: 'ligues', label: 'Ligues', icon: '⚽' },
          { id: 'joueurs_ligues', label: 'Joueurs des Ligues', icon: '👥' },
          { id: 'centres_formation', label: 'Centres de Formation', icon: '🎓' }
        ].map((tab) => (
          <button
            key={tab.id}
            onClick={() => setActiveSubTab(tab.id)}
            className={`px-4 py-2 rounded-lg font-medium text-sm transition-colors duration-200 flex items-center space-x-2 ${
              activeSubTab === tab.id
                ? 'bg-green-600 text-white'
                : 'bg-gray-200 text-gray-700 hover:bg-gray-300'
            }`}
          >
            <span>{tab.icon}</span>
            <span>{tab.label}</span>
          </button>
        ))}
      </div>

      {/* Contenu des sous-onglets */}
      {activeSubTab === 'equipe_nationale' && (
        <div className="bg-white rounded-xl shadow-lg p-6">
          <h3 className="text-2xl font-bold mb-6 text-gray-800">{donneesPays[selectedCountry]?.equipeNationale.nom}</h3>
          <div className="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div>
              <div className="mb-6">
                <h4 className="font-semibold text-lg mb-3">Informations Générales</h4>
                <div className="space-y-2">
                  <div className="flex justify-between">
                    <span className="text-gray-600">Surnom:</span>
                    <span className="font-semibold">{donneesPays[selectedCountry]?.equipeNationale.surnom}</span>
                  </div>
                  <div className="flex justify-between">
                    <span className="text-gray-600">Entraîneur:</span>
                    <span className="font-semibold">{donneesPays[selectedCountry]?.equipeNationale.entraineur}</span>
                  </div>
                  <div className="flex justify-between">
                    <span className="text-gray-600">Classement FIFA:</span>
                    <span className="font-semibold">{donneesPays[selectedCountry]?.equipeNationale.classementFIFA}</span>
                  </div>
                </div>
              </div>
              
              <div>
                <h4 className="font-semibold text-lg mb-3">Trophées</h4>
                <div className="space-y-2">
                  {donneesPays[selectedCountry]?.equipeNationale.trophes.map((trophee, index) => (
                    <div key={index} className="bg-gray-50 p-3 rounded-lg">
                      <div className="font-semibold">{trophee.nom}</div>
                      <div className="text-sm text-gray-600">
                        {trophee.annees.join(', ')}
                      </div>
                    </div>
                  ))}
                </div>
              </div>
            </div>
            
            <div>
              <h4 className="font-semibold text-lg mb-3">Joueurs Clés</h4>
              <div className="space-y-3">
                {donneesPays[selectedCountry]?.equipeNationale.joueurs.map((joueur, index) => (
                  <div key={index} className="flex items-center justify-between p-3 bg-gray-50 rounded-lg">
                    <div>
                      <div className="font-semibold">{joueur.nom}</div>
                      <div className="text-sm text-gray-600">{joueur.position} • {joueur.age} ans</div>
                    </div>
                    <div className="text-sm font-semibold text-green-600">{joueur.club}</div>
                  </div>
                ))}
              </div>
            </div>
          </div>
        </div>
      )}

      {activeSubTab === 'ligues' && (
        <div className="bg-white rounded-xl shadow-lg p-6">
          <h3 className="text-2xl font-bold mb-6 text-gray-800">Ligues de {selectedCountry}</h3>
          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            {donneesPays[selectedCountry]?.ligues.map((ligue, index) => (
              <div key={index} className="border border-gray-200 rounded-lg p-4 hover:shadow-md transition-shadow duration-200">
                <div className="flex justify-between items-start mb-3">
                  <h4 className="font-bold text-lg">{ligue.nom}</h4>
                  <span className="bg-green-100 text-green-800 text-xs px-2 py-1 rounded-full">
                    Niveau {ligue.niveau}
                  </span>
                </div>
                <div className="space-y-2 text-sm">
                  <div className="flex justify-between">
                    <span className="text-gray-600">Clubs:</span>
                    <span className="font-semibold">{ligue.clubs}</span>
                  </div>
                  <div className="flex justify-between">
                    <span className="text-gray-600">Champion actuel:</span>
                    <span className="font-semibold">{ligue.championActuel}</span>
                  </div>
                </div>
              </div>
            ))}
          </div>
        </div>
      )}

      {activeSubTab === 'joueurs_ligues' && (
        <div className="bg-white rounded-xl shadow-lg p-6">
          <h3 className="text-2xl font-bold mb-6 text-gray-800">Joueurs des Ligues - {selectedCountry}</h3>
          <div className="overflow-x-auto">
            <table className="w-full">
              <thead className="bg-gray-50 border-b">
                <tr>
                  <th className="text-left p-4 font-semibold text-gray-700">Joueur</th>
                  <th className="text-left p-4 font-semibold text-gray-700">Position</th>
                  <th className="text-left p-4 font-semibold text-gray-700">Âge</th>
                  <th className="text-left p-4 font-semibold text-gray-700">Club</th>
                </tr>
              </thead>
              <tbody className="divide-y">
                {donneesPays[selectedCountry]?.joueursLigues.map((joueur, index) => (
                  <tr key={index} className="hover:bg-gray-50 transition-colors duration-150">
                    <td className="p-4 font-semibold text-gray-800">{joueur.nom}</td>
                    <td className="p-4 text-gray-600">{joueur.position}</td>
                    <td className="p-4 text-gray-600">{joueur.age} ans</td>
                    <td className="p-4 text-gray-600">{joueur.club}</td>
                  </tr>
                ))}
              </tbody>
            </table>
          </div>
        </div>
      )}

      {activeSubTab === 'centres_formation' && (
        <div className="bg-white rounded-xl shadow-lg p-6">
          <h3 className="text-2xl font-bold mb-6 text-gray-800">Centres de Formation - {selectedCountry}</h3>
          <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
            {donneesPays[selectedCountry]?.centresFormation.map((centre, index) => (
              <div key={index} className="border border-gray-200 rounded-lg p-6">
                <h4 className="font-bold text-lg mb-3">{centre.nom}</h4>
                <div className="space-y-2 text-sm">
                  <div className="flex justify-between">
                    <span className="text-gray-600">Ville:</span>
                    <span className="font-semibold">{centre.ville}</span>
                  </div>
                  <div className="flex justify-between">
                    <span className="text-gray-600">Fondateur:</span>
                    <span className="font-semibold">{centre.fondateur}</span>
                  </div>
                  <div className="flex justify-between">
                    <span className="text-gray-600">Année de création:</span>
                    <span className="font-semibold">{centre.anneeCreation}</span>
                  </div>
                </div>
              </div>
            ))}
          </div>
        </div>
      )}
    </div>
  );

  const renderClubs = () => (
    <div className="space-y-6">
      <div className="flex justify-between items-center">
        <h2 className="text-3xl font-bold text-gray-800">Clubs</h2>
        <div className="relative w-64">
          <input
            type="text"
            placeholder="Rechercher un club..."
            value={searchQuery}
            onChange={(e) => setSearchQuery(e.target.value)}
            className="w-full px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-green-500"
          />
        </div>
      </div>

      <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
        {clubs.map((club) => (
          <div key={club.id} className="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <div className="p-6 text-center">
              <img src={club.logo} alt={club.nom} className="w-20 h-20 mx-auto mb-4 rounded-full" />
              <h3 className="text-xl font-bold text-gray-800 mb-2">{club.nom}</h3>
              <p className="text-gray-600 mb-1">{club.ville}, {club.pays}</p>
              <p className="text-gray-500 text-sm mb-3">{club.stade}</p>
              
              <div className="border-t pt-3">
                <div className="flex justify-between text-sm mb-1">
                  <span className="text-gray-600">Fondé en</span>
                  <span className="font-semibold">{club.fondation}</span>
                </div>
                <div className="flex justify-between text-sm mb-1">
                  <span className="text-gray-600">Président</span>
                  <span className="font-semibold">{club.president}</span>
                </div>
                <div className="flex justify-between text-sm mb-1">
                  <span className="text-gray-600">Entraîneur</span>
                  <span className="font-semibold">{club.entraineur}</span>
                </div>
                <div className="flex justify-between text-sm mb-1">
                  <span className="text-gray-600">Capacité</span>
                  <span className="font-semibold">{club.capacite.toLocaleString()}</span>
                </div>
                <div className="flex justify-between text-sm">
                  <span className="text-gray-600">Valeur</span>
                  <span className="font-semibold text-green-600">{club.valeur}</span>
                </div>
              </div>
            </div>
          </div>
        ))}
      </div>
    </div>
  );

  const renderJoueurs = () => (
    <div className="space-y-6">
      <div className="flex justify-between items-center">
        <h2 className="text-3xl font-bold text-gray-800">Joueurs</h2>
        <div className="relative w-64">
          <input
            type="text"
            placeholder="Rechercher un joueur..."
            value={searchQuery}
            onChange={(e) => setSearchQuery(e.target.value)}
            className="w-full px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-green-500"
          />
        </div>
      </div>

      <div className="bg-white rounded-xl shadow-lg overflow-hidden">
        <div className="overflow-x-auto">
          <table className="w-full">
            <thead className="bg-gray-50 border-b">
              <tr>
                <th className="text-left p-4 font-semibold text-gray-700">Joueur</th>
                <th className="text-left p-4 font-semibold text-gray-700">Position</th>
                <th className="text-left p-4 font-semibold text-gray-700">Âge</th>
                <th className="text-left p-4 font-semibold text-gray-700">Club</th>
                <th className="text-left p-4 font-semibold text-gray-700">Équipe Nationale</th>
                <th className="text-left p-4 font-semibold text-gray-700">Buts (saison)</th>
              </tr>
            </thead>
            <tbody className="divide-y">
              {joueurs.map((joueur) => (
                <tr key={joueur.id} className="hover:bg-gray-50 transition-colors duration-150">
                  <td className="p-4">
                    <div className="flex items-center">
                      <div className="w-10 h-10 bg-gray-300 rounded-full mr-3 flex items-center justify-center">
                        <span className="text-sm font-semibold text-gray-600">
                          {joueur.nom.charAt(0)}{joueur.prenoms.charAt(0)}
                        </span>
                      </div>
                      <div>
                        <div className="font-semibold text-gray-800">{joueur.nom} {joueur.prenoms}</div>
                        <div className="text-xs text-gray-500">{joueur.nationalites.join(', ')}</div>
                      </div>
                    </div>
                  </td>
                  <td className="p-4 text-gray-600">{joueur.positions.join(', ')}</td>
                  <td className="p-4 text-gray-600">{joueur.statsSaison.matchsJoues} ans</td>
                  <td className="p-4 text-gray-600">{joueur.clubActuel}</td>
                  <td className="p-4">
                    <span className="bg-green-100 text-green-800 text-xs px-2 py-1 rounded-full">
                      {joueur.equipeNationale}
                    </span>
                  </td>
                  <td className="p-4 font-semibold text-green-600">{joueur.statsSaison.buts}</td>
                </tr>
              ))}
            </tbody>
          </table>
        </div>
      </div>
    </div>
  );

  const renderOfficiels = () => (
    <div className="space-y-6">
      <div className="flex justify-between items-center">
        <h2 className="text-3xl font-bold text-gray-800">Officiels</h2>
        <div className="relative w-64">
          <input
            type="text"
            placeholder="Rechercher un officiel..."
            value={searchQuery}
            onChange={(e) => setSearchQuery(e.target.value)}
            className="w-full px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-green-500"
          />
        </div>
      </div>

      <div className="bg-white rounded-xl shadow-lg overflow-hidden">
        <div className="overflow-x-auto">
          <table className="w-full">
            <thead className="bg-gray-50 border-b">
              <tr>
                <th className="text-left p-4 font-semibold text-gray-700">Nom</th>
                <th className="text-left p-4 font-semibold text-gray-700">Fonction</th>
                <th className="text-left p-4 font-semibold text-gray-700">Nationalité</th>
                <th className="text-left p-4 font-semibold text-gray-700">Expérience</th>
                <th className="text-left p-4 font-semibold text-gray-700">Palmarès</th>
              </tr>
            </thead>
            <tbody className="divide-y">
              {officiels.map((officiel) => (
                <tr key={officiel.id} className="hover:bg-gray-50 transition-colors duration-150">
                  <td className="p-4">
                    <div className="flex items-center">
                      <img src={officiel.photo} alt={officiel.nom} className="w-10 h-10 rounded-full mr-3" />
                      <div>
                        <div className="font-semibold text-gray-800">{officiel.nom}</div>
                        <div className="text-sm text-gray-600">{officiel.dateNaissance}</div>
                      </div>
                    </div>
                  </td>
                  <td className="p-4 text-gray-600">{officiel.fonction}</td>
                  <td className="p-4 text-gray-600">{officiel.nationalite}</td>
                  <td className="p-4">
                    <div className="text-sm">
                      {officiel.experience[0].equipe} ({officiel.experience[0].debut}-{officiel.experience[0].fin})
                    </div>
                  </td>
                  <td className="p-4 text-sm text-gray-600">
                    {officiel.palmares.length} trophée{officiel.palmares.length > 1 ? 's' : ''}
                  </td>
                </tr>
              ))}
            </tbody>
          </table>
        </div>
      </div>
    </div>
  );

  const renderBlog = () => (
    <div className="space-y-6">
      <div className="flex justify-between items-center">
        <h2 className="text-3xl font-bold text-gray-800">Blog Football Africain</h2>
        <div className="relative w-64">
          <input
            type="text"
            placeholder="Rechercher un article..."
            value={searchQuery}
            onChange={(e) => setSearchQuery(e.target.value)}
            className="w-full px-4 py-2 rounded-lg border border-gray-300 focus:outline-none focus:ring-2 focus:ring-green-500"
          />
        </div>
      </div>

      <div className="grid grid-cols-1 lg:grid-cols-2 gap-6">
        {filteredArticles.map((article) => (
          <div key={article.id} className="bg-white rounded-xl shadow-lg overflow-hidden hover:shadow-xl transition-shadow duration-300">
            <img src={article.image} alt={article.titre} className="w-full h-48 object-cover" />
            <div className="p-6">
              <div className="flex items-center mb-3">
                <span className="text-sm text-gray-500">{article.date}</span>
                <span className="mx-2">•</span>
                <span className="text-sm text-green-600">Par {article.auteur}</span>
              </div>
              <h3 className="text-xl font-bold text-gray-800 mb-3">{article.titre}</h3>
              <p className="text-gray-600 mb-4">{article.resume}</p>
              <button 
                onClick={() => setActiveSubTab(article.id)}
                className="text-green-600 font-semibold hover:text-green-800 transition-colors duration-200"
              >
                Lire la suite →
              </button>
            </div>
          </div>
        ))}
      </div>
    </div>
  );

  return (
    <div className="min-h-screen bg-gray-50">
      {/* Header */}
      <header className="bg-gradient-to-r from-green-600 via-blue-600 to-orange-500 text-white shadow-lg">
        <div className="container mx-auto px-4 py-6">
          <div className="flex flex-col md:flex-row justify-between items-center">
            <div className="flex items-center mb-4 md:mb-0">
              <div className="w-12 h-12 bg-white rounded-full flex items-center justify-center mr-4">
                <span className="text-2xl font-bold text-green-600">AF</span>
              </div>
              <div>
                <h1 className="text-3xl font-bold">FootAfrique</h1>
                <p className="text-green-100">Le portail du football africain</p>
              </div>
            </div>
            <div className="relative w-full md:w-64">
              <input
                type="text"
                placeholder="Rechercher..."
                value={searchQuery}
                onChange={(e) => setSearchQuery(e.target.value)}
                className="w-full px-4 py-2 rounded-lg text-gray-800 focus:outline-none focus:ring-2 focus:ring-white"
              />
              <svg className="absolute right-3 top-2.5 w-5 h-5 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
              </svg>
            </div>
          </div>
        </div>
      </header>

      {/* Navigation */}
      <nav className="bg-white shadow-md">
        <div className="container mx-auto px-4">
          <div className="flex space-x-8 overflow-x-auto">
            {[
              { id: 'accueil', label: 'ACCUEIL', icon: '🏠' },
              { id: 'pays', label: 'PAYS', icon: '🌍' },
              { id: 'clubs', label: 'CLUBS', icon: '⚽' },
              { id: 'joueurs', label: 'JOUEURS', icon: '👥' },
              { id: 'officiels', label: 'OFFICIELS', icon: '👔' },
              { id: 'blog', label: 'BLOG', icon: '📝' }
            ].map((tab) => (
              <button
                key={tab.id}
                onClick={() => {
                  setSelectedTab(tab.id);
                  if (tab.id === 'pays') setActiveSubTab('equipe_nationale');
                  if (tab.id === 'blog') setActiveSubTab(null);
                }}
                className={`py-4 px-2 border-b-2 font-medium text-sm whitespace-nowrap transition-colors duration-200 flex items-center space-x-2 ${
                  selectedTab === tab.id
                    ? 'border-green-600 text-green-600'
                    : 'border-transparent text-gray-500 hover:text-green-600 hover:border-green-300'
                }`}
              >
                <span>{tab.icon}</span>
                <span>{tab.label}</span>
              </button>
            ))}
          </div>
        </div>
      </nav>

      {/* Main Content */}
      <main className="container mx-auto px-4 py-8">
        {selectedTab === 'accueil' && renderAccueil()}
        {selectedTab === 'pays' && renderPays()}
        {selectedTab === 'clubs' && renderClubs()}
        {selectedTab === 'joueurs' && renderJoueurs()}
        {selectedTab === 'officiels' && renderOfficiels()}
        {selectedTab === 'blog' && renderBlog()}
      </main>

      {/* Footer */}
      <footer className="bg-gray-800 text-white mt-16">
        <div className="container mx-auto px-4 py-12">
          <div className="grid grid-cols-1 md:grid-cols-4 gap-8">
            <div>
              <div className="flex items-center mb-4">
                <div className="w-10 h-10 bg-green-500 rounded-full flex items-center justify-center mr-3">
                  <span className="text-lg font-bold text-white">AF</span>
                </div>
                <span className="text-xl font-bold">FootAfrique</span>
              </div>
              <p className="text-gray-400 mb-4">Votre source complète pour toutes les informations sur le football africain.</p>
              <div className="flex space-x-4">
                <a href="#" className="text-gray-400 hover:text-white transition-colors duration-200">Facebook</a>
                <a href="#" className="text-gray-400 hover:text-white transition-colors duration-200">Twitter</a>
                <a href="#" className="text-gray-400 hover:text-white transition-colors duration-200">Instagram</a>
              </div>
            </div>
            <div>
              <h3 className="font-semibold mb-4">Navigation</h3>
              <ul className="space-y-2 text-gray-400">
                <li><a href="#" className="hover:text-white transition-colors duration-200">Accueil</a></li>
                <li><a href="#" className="hover:text-white transition-colors duration-200">Pays</a></li>
                <li><a href="#" className="hover:text-white transition-colors duration-200">Clubs</a></li>
                <li><a href="#" className="hover:text-white transition-colors duration-200">Joueurs</a></li>
              </ul>
            </div>
            <div>
              <h3 className="font-semibold mb-4">Compétitions</h3>
              <ul className="space-y-2 text-gray-400">
                <li><a href="#" className="hover:text-white transition-colors duration-200">Coupe d'Afrique des Nations</a></li>
                <li><a href="#" className="hover:text-white transition-colors duration-200">Ligue des Champions</a></li>
                <li><a href="#" className="hover:text-white transition-colors duration-200">Coupe de la Confédération</a></li>
                <li><a href="#" className="hover:text-white transition-colors duration-200">Jeux Africains</a></li>
              </ul>
            </div>
            <div>
              <h3 className="font-semibold mb-4">Contact</h3>
              <ul className="space-y-2 text-gray-400">
                <li>contact@footafrique.ci</li>
                <li>+225 22 44 55 66</li>
                <li>Abidjan, Côte d'Ivoire</li>
              </ul>
            </div>
          </div>
          <div className="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400">
            <p>&copy; 2024 FootAfrique. Tous droits réservés.</p>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default App;
