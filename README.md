# rizzastro-website
Modern Astronomy Website - Explore the cosmos with Rizzastro"
import Head from 'next/head'
import Hero from '../components/Hero'
import Features from '../components/Features'
import Gallery from '../components/Gallery'
import Navigation from '../components/Navigation'
import Footer from '../components/Footer'

export default function Home() {
  return (
    <>
      <Head>
        <title>Rizzastro - Explore the Cosmos</title>
        <meta name="description" content="Discover the wonders of astronomy with Rizzastro. Learn about stars, planets, galaxies, and the universe." />
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        <link rel="icon" href="/favicon.ico" />
      </Head>
      <main className="bg-gradient-cosmos min-h-screen">
        <Navigation />
        <Hero />
        <Features />
        <Gallery />
        <Footer />
      </main>
    </>
  )
}
